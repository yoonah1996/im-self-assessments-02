## Chat Client
This repository is a chat-client like the one you built for Chatterbox Client. It has a (mostly) completed HTML/CSS user interface, but is missing a critical feature:
go visit https://jsonplaceholder.typicode.com and see the fake api resource for posts (GET and POST)
You will use this resource for this assessment.

* [ ] Inside `js/setup.js`, locate the function responsible for sending a post to the server and write a comment to indicate your claim / 한글: `js/setup.js` 에서 서버로 포스트를 보내는 함수를 찾아 구현하세요.
* [ ] In the method that you identified, make it so that any post sent to the server appears in the chat log along with other latest posts as soon as the client knows that the server successfully received them, rather than waiting for a refresh or the timed update (refer to the post id for sorting data) / 한글: 포스트를 성공적으로 보내면 성공적으로 보낸 메시지와 함께 서버에 업데이트 된 모든 포스트 들을 브라우저 상에 포스트 된 최신 순으로 보이게 해 주세요. (포스트 id 참조)

Note that this is an exercise in reading api document and reading code, so expect to spend most of your time figuring out where to make changes and try to write as little code as possible

### Available Resources for this Prompt
* jQuery docs
* MDN
* https://jsonplaceholder.typicode.com


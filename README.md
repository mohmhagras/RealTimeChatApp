# Real Time Chat App
A full stack real time chat web app built using .NET Core, SignalR, MongoDB, Typescript, Firebase storage & Next.JS. Optimized for usage on dektop and mobile.
# Codes

 - Client code: https://github.com/mohagras903/RealTimeChatClient
 - Server code: https://github.com/mohagras903/RealTimeChatServer

## Live URL:
https://rtchatclient.vercel.app/

## Features
- Register & Login: with loading and error states.
<table>
  <tr>
  <td valign="top">
<img  alt="Register page" src="https://user-images.githubusercontent.com/64911020/211501435-aaa7220e-a375-4604-b027-ed24cd37bfc0.PNG">
</td>
  <td valign="top">
<img  alt="duplicate username error" src="https://user-images.githubusercontent.com/64911020/211506104-4cf92cfe-9871-415c-96b6-013ab0d33ed7.PNG">
</td>
  <td valign="top">
<img  alt="Register page loading" src="https://user-images.githubusercontent.com/64911020/211507617-6e715f5d-c998-4321-95ce-32d1384a2680.PNG">
</td>
  </tr>
</table>

- Chat Screen Dashboard: Chats, Friend Requests, Friends List. You can start a new chat with a friend by clicking on the friend item in the list.
<table>
  <tr>
  <td valign="top">
<img width="300" alt="Dashboard screen of a brand new account" src="https://user-images.githubusercontent.com/64911020/211508878-52454642-74b0-42b9-8159-1aa02668e17e.PNG">
</td>
  <td valign="top">
<img width="300"  alt="Dashboard page after adding 2 friends" src="https://user-images.githubusercontent.com/64911020/211509225-880af0fe-b66a-4e93-ab6e-0724bb0e484f.PNG">
</td>
  </tr>
</table>

- Send new friend request by username:
<table>
  <tr>
  <td valign="top">
<img width="300"  alt="Send Friend Request" src="https://user-images.githubusercontent.com/64911020/211510225-ac802278-51f5-4e12-826e-324bd7009b96.PNG">
</td>
  </tr>
</table>

- Friend requests screen: list of requests displayed, each request has the sender's username, photo and the of mutual friends with options to accept or ignore.
<table>
  <tr>
  <td valign="top">
<img width="300"  alt="Friend request from user with no mutual friends" src="https://user-images.githubusercontent.com/64911020/211510764-fd8022e0-3cfe-4708-9dfd-c493927cd51f.PNG">
</td>
  <td valign="top">
<img width="300" alt="Friend request from a user with mutual friends" src="https://user-images.githubusercontent.com/64911020/211510862-d9af5f0c-a66c-47dc-a45b-dac56b2e15d2.PNG">
</td>
  </tr>
</table>

- Change profile photo page: upload new img as the profile photo.
<table>
  <tr>
  <td valign="top">
<img width="300" alt="Change photo page" src="https://user-images.githubusercontent.com/64911020/211521833-49893f4a-6f98-4e53-a033-f4d4dac6fe88.PNG">
</td>
  </tr>
</table>

- Chats screen: list of chats sorted based on last activity date. Each chat has  the last message sent displayed.
<table>
  <tr>
  <td valign="top">
<img width="300" alt="Register page" src="https://user-images.githubusercontent.com/64911020/211520803-537f16d4-2fe2-407e-95fa-f51d215a75fd.PNG">
</td>
  <td valign="top">
<img width="300" alt="Register page" src="https://user-images.githubusercontent.com/64911020/211521604-06cb3785-ce0d-4c02-9b72-017076d28184.PNG">
</td>
  </tr>
</table>


- Chat box: displays the messages sent between the two users in the selected chat. Each message has a time stamp on it (date + time if message not sent today, time only if sent today).
<table>
  <tr>
  <td valign="top">
<img width="300" alt="Register page" src="https://user-images.githubusercontent.com/64911020/211522471-30df95e3-5a71-491e-b53b-bcc6a7698d54.PNG">
</td>
  <td valign="top">
<img width="300" alt="Register page" src="https://user-images.githubusercontent.com/64911020/211529296-7a373c65-6974-4463-bc45-351c89365263.PNG">
</td>
  </tr>
</table>


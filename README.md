# zchat

An online chat platform based on `django`

## Blog

The prototype of a social media

### Signup

You will be redirected to `/signup/?next=/` for signing up, and you call also choose to login if already have the account.

<img src="D:\大工杂项\web技术\大作业\signup.png" alt="signup" style="zoom:80%;" />

After signing up, you will need to create your profile by entering your `Username`, `Fname`, `Lname`, `Description` and upload your `Profileimg`

<img src="D:\大工杂项\web技术\大作业\create_user_profile.png" alt="create_user_profile" style="zoom:80%;" />

Now you can visit the `Zchat` homepage!

### Home

In the homepage, you can visit almost all units of the `Zchat`, and it shows the posts created and suggested users.

<img src="D:\大工杂项\web技术\大作业\homepage.png" alt="homepage" style="zoom:80%;" />

You can click the `Heart` to like the post or click the `Comment` to add your comment.

### Profile

To customize your profile, just click the `Edit Profile`, and you will visit the `Edit Profile Page`, almost like the `Create Profile Page` when you first sign up your account

To view your profile, you can just click your avatar or click the `Profile`

### Post

To create your post, just click the `Add Post`

<img src="D:\大工杂项\web技术\大作业\Add_Post.png" alt="Add_Post" style="zoom:80%;" />

In the `Add Post Page`, you will need to provide the `Title`, `Title Tag`, `Author`, `Caption`, `Location` and `Image` of your post. After creating your post, you can check it in your homepage.

### Friend

You can follow others by clicking one's avatar in the `User Suggestions` menu, or search the username in the searching area.

## Videocall

`/videocall`

Using WebRTC to implement real-time online video communication.

You and your friend can use the `Zchat Videocall` to communicate anonymously. Just enter your name and your friend's name, and it's all done.

⚠️⚠️⚠️

WebSocket requires the safe `http` connection (aka `https`). If you're just test the project locally, you can just ignore this. If not, try to get `SSL/TLS` or simply use `SSH Reverse Proxy` like the following command:

```bash
$ ssh -CfNg -L {LOCAL_PORT}:{IP}:{REMOTE_PORT} {USERNAME}@{IP} -p {SSH_PORT}
```


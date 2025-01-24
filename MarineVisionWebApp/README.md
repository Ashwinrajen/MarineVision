# MarineVision Web Application- Developed by Jithin Krishnan

This is a Python Flask Web Application that accepts a video, make api call to other video enhancement applications and retun the enhanced videos

Along with that applictaion also make use of a Hybrid 3D-CNN and LSTM Autoencoder​ based Best Video Selection algorith to let user know which output video is the best


Process Flow:​
​
- User uploads an input video via the frontend.​
- Backend server sends the video to multiple model APIs for enhancement.​
- The Best Video Selection Model determines the highest-quality output.​
- The enhanced video is sent back to the user via the frontend.​
- As an optional feature, the user can also provide feedback on the users deemed best video is different

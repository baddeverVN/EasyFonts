# EasyFonts
Hướng dẫn sử dụng tạo custom font :
1. Copy 2 class trong package customfont
2. copy tiếp bộ raw 
3. sửa lỗi liên quan
4. tùy ý chình sửa bộ raw và trong class EasyFonts
5. set Font bằng  :
   TextView textView = (TextView) findViewById(R.id.txt_hello);
   textView.setTypeface(EasyFonts.droidRobot(this));

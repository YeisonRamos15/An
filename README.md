var Text = createjs.Text(
"Entre tantas estrellas, tu\
eres mi favorita an",
"bold 24px Arial", "#fff");
text.textAlign = "center";
text.x =  W / 2;
text.y =  H / 2 - text. getMeasuredLineHeight();
stage.addChild(text);

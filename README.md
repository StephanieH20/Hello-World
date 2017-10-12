# Hello-World
echo "# Hello-World" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/StephanieH20/Hello-World.git
git push -u origin master

void fillPixel(int x, int y) {
rect(x, y, 1, 1);
}

void floodFill(int r, int c) {
if(r < 0 || r > screen.length || c < 0 || c > screen.width) {
return;
}
fillPixel(r, c);
floodFill(r + 1, c);
floodFill(r - 1, c);
floodFill(r, c + 1);
floodFill(r, c - 1);
}
}

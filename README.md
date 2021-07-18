# Gulp_example

21.07.18 일_Learn Gulp by building an awesome development environment         

Gulp 는 반복적인 작업이나 프론트엔드 빌드에 필요한 작업들을 처리할 수 있게 도와주는 빌드 툴이다.   
<br>
<br>
node version이 높아 scss가 안되는 상황 발생

import sass from "gulp-sass";  
sass.compiler = require("node-sass");

이게 되지 않음. 해결방법은 nvm으로 node 버전을 14.0 이하로 낮춰야함.

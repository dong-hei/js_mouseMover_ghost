# js_mouseMover_ghost

★css
ghost 그림

★js
  document.body.addEventListener("mousemove",function(e){
            document.querySelector('.ghost').style.left = e.pageX + 'px';
            document.querySelector('.ghost').style.top = e.pageY + 'px';
            })
            
mousemove 이벤트 선언시 괄호안에있는 querySelector를 지정할시 마우스를 따라감
left = pageX의 px 좌표에 따라서 이동함
top = pageY의 px 좌표에 따라서 이동함

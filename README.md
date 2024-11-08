## My name is Cat
![this is img](https://c.pxhere.com/photos/9a/56/kitten_cat_feline_yellow_red_portrait_watching_pet-1338723.jpg!s1)

**I`m javascript developer**.*There is Example of my code*
```javascript
let input = document.getElementById("TEXT");
      	  let button = document.getElementById("BUTTON");
      	  let list = document.getElementById("LIST");

      	  let n;
      	  if(localStorage.getItem(`n`) == null){
      	  	n = 0;
      	  }else{
      	  	n = localStorage.getItem(`n`) - 1 + 1;
      	  }

      	  ONload()
      	  button.addEventListener('click',function(){
      	  	 let text = input.value;
      	  	 let li = document.createElement('li');
      	  	 li.innerHTML = `<li>${text}</li>`;
      	  	 save(text);
      	  	 list.append(li);
      	  	 input.value = ``;
      	  })
      	  function save(text){
      	  	n+=1
      	  	localStorage.setItem(`n`, n);
      	  	localStorage.setItem(`text${n}`, text);

      	  }
      	  function ONload(){
      	  	list.innerHTML = ``;
      	  		for (let i = 1; i<= localStorage.length - 1; i++){
      	  		let text = localStorage.getItem(`text${i}`)
      	  		let li = document.createElement('li')
      	  		li.innerHTML = `<li>${text}</li>`
      	  		list.append(li);
      	  		
      	  }
      	}
```
This is list:
* Item 1
* Item 2
* Item 3

[Jojo episode 1 season 1](https://jut.su/jojo-bizarre-adventure/season-1/episode-1.html)

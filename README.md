# guessing_game
<script> 
  (function()  {
 	var answer = "5";

 	var guess = prompt('How many Nintendo characters can you name?');
 	guess = Number.parseInt(guess);
 	while (true)  {
 		if (guess == answer)  {
 			alert('I bet you can name more')
 			break;
 		}  else if (guess > answer)  {
 			alert('That\'s awesome!')
 			break;
 		}  else if (guess < answer)  {
 			alert('You can do better than that!')
 			break;
 		}
 	}
 	
 	var guess2 = prompt('Name one') ;
 	while (true) {
 		if (guess2 === 'Mario') {
 			alert('That\'s one!'); 
 			break;
 		} else if (guess2 === 'Luigi') {
 			alert('That\'s one!') ;
 			break;
 		} else {
 			alert('wrong try again');
 			guess2 = prompt('What is one?');
 		}
 	}	
 	
 	var guess3 = prompt('Can you name another one?');
 	while (true)  {
 		if (guess3 === 'Mario')  {
 			alert('That\'s another one!');
 		} else if (guess3 === 'Luigi')  {
 			alert('You got it!');
 		} else {
 			alert('Wrong try again!')
 			guess3 = prompt('Can you name another one?');
 		}
 	}

  }) ();

</script>

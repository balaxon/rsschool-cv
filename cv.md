# **Aliaksandr Balahanau** 
## Contact Info:
* E-mail: balahanov2209@gmail.com
* Phone number: +375 44 783 46 99
## Summary:
* Analytical thinking
*  Teamwork
*   Learnability
## Skills:
### Basic knowledge in:
* HTML
* CSS
* JavaScript
* SQL
* OOP
* Git
* Hardware
## Code examples:
    function solution(input, markers) { 
	    markers = markers.toString().split(','); 
	    input = input.split('\n')
	    let result = ''; 
	    let prom=''; 
	    for (let i=0;i<input.length;i++) 
	    { 
			for(let k=0;k<markers.length;k++) 
			{
				if(input[i].includes(markers[k])==true){
 				input[i]=input[i].split(markers[k])[0]} 
 			}
 				result=result+input[i].trim()+'\n'; 
 		} 
 			return result.trim(); 
 	};
## Experience:
#### Not yet
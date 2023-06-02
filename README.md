
# CGC- FSS

CGC-FSS is a scheduling system built for CGC (CITI Global College) that allows the scheduler to automate the scheduling process. Deployed on ph.000webhost.

<i>**Demo Account:**</i>
<br/>`Username: demo`
<br/>`Password: demo1234$`



## Algorithm

Binary Search Algorithm used to process scheduling.

```bash
  function binarySearch(arr, x) {
	let start = 0;
	let end = arr.length - 1;

	while (start <= end) {
		let mid = Math.floor((start + end) / 2);

		if (arr[mid] === x) {
			return mid;
		}

		if (arr[mid] < x) {
			start = mid + 1;
		} else {
			end = mid - 1;
		}
	}
	return -1;
}
```


## Features

- Instructor Module
- Curriculum Management Module
- Maintenance Management Module
- Report Module
- Timetable Module


## Screenshots
- Log in
![App Screenshot](https://ppacris.github.io/portfolio/assets/image/cgc-fss_login.png)

- Home page
![App Screenshot](https://ppacris.github.io/portfolio/assets/image/cgc-fss_home.png)


## 🛠 Technology & Tools
<a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/></a>
<a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/></a>
<a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/></a>

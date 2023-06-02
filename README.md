
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

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original.svg" height="40" alt="chrome logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/composer/composer-original.svg" height="40" alt="composer logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="40" alt="bootstrap logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" height="40" alt="jquery logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="40" alt="php logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/mysql/4479A1" height="40" alt="mysql logo"  />
</div>

###


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

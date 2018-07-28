
# cookie.js 
> * [Installation](#installation)
> * [Usage](#usage)
> * [Contributing](#contributing)

---
Simple and light javascript functions for handling cookies, such as the [jquery-cookie](https://github.com/carhartl/jquery-cookie/) project, but without the need of the Jquery library.



## Installation
---
Clone repository.
```git
git clone https://github.com/leoallvez/cookie.js.git
```
Set the file path in HTML
```html
<script src="/path/to/cookie.js"></script>
```
## Usage
---

Create session cookie:

```javascript
setCookie('name', 'value');
```
Read cookie:

```javascript
getCookie('name'); // "The cookie value"
getCookie('nothing'); //false
```

Delete cookie:
```javascript
removeCookie('name'); // void
```

## Contributing
___

- :star2: Place this project in your favorites with a Star
- :fork_and_knife: Make a Project Fork
- :computer: Clone the repository to your computer
- :wrench: Contribute in the code or documentation of the Project
- :point_right: Create a commit with the changes and make a Pull Request (PR)
- :tada: See your Pull Request approved and repeat the cycle!

New issues should be opened at https://github.com/leoallvez/cookie.js/issues
___
## Author
[Leonardo Pereira Alves](https://github.com/leoallvez)




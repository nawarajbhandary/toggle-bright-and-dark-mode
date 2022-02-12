# toggle-bright-and-dark-mode

## JS code to define body class dark 


``` 
let toggle = document.getElementById("mode");

toggle.addEventListener("click", () => {
  document.body.classList.toggle("dark");
});

```

##Pseudoclass to implement toggle button 

```shell


input[type="checkbox"] {
  -webkit-appearance: none;
  position: relative;
  width: 80px;
  height: 40px;
  border-radius: 50px;
  outline: none;
  background-color: rgb(172, 163, 163);
}

input[type="checkbox"]::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 40px;
  width: 40px;
  background-color: var(--primary-dark);
  border-radius: 50px;
}

input[type="checkbox"]:checked::before {
  transform: translate(100%);
}

input[type="checkbox"]:checked {
  background-color: black;
}

```

`Use of var to impletement Dark and Light theme in CSS` 

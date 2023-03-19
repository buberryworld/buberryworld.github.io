/* Define Solarized colors */
:root {
  --base03: #002b36;
  --base02: #073642;
  --base01: #586e75;
  --base00: #657b83;
  --base0: #839496;
  --base1: #93a1a1;
  --base2: #eee8d5;
  --base3: #fdf6e3;
  --yellow: #b58900;
  --orange: #cb4b16;
  --red: #dc322f;
  --magenta: #d33682;
  --violet: #6c71c4;
  --blue: #268bd2;
  --cyan: #2aa198;
  --green: #859900;
}



/* Apply Solarized colors to the terminal */
#terminal {
margin: 0 auto;
background-color: var(--base03);
color: var(--base0);
font-family: 'Courier New', Courier, monospace;
font-size: 16px;
padding: 0px;
height: 728px;
overflow-y: auto;
border: 5px solid #555;
max-width: 60%;
}

/* Style the links */
#terminal a {
color: var(--blue);
}

#terminal a:hover {
color: var(--cyan);
} 

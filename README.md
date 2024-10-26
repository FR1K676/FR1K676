<style>
    body {
      margin: 0;
      overflow: hidden;
      background-color: #f0f0f0;
    }
    #worm {
      position: absolute;
      width: 50px;
      height: 20px;
      background-color: green;
      border-radius: 50% 50% 0 0;
      transform-origin: 50% 100%;
      animation: wiggle 0.5s infinite alternate;
    }
    @keyframes wiggle {
      0% { transform: rotate(0deg); }
      50% { transform: rotate(-10deg); }
      100% { transform: rotate(10deg); }
    }
  </style>
  <div id="worm"></div>

  <script>
    const worm = document.getElementById('worm');
    
    window.addEventListener('mousemove', (event) => {
      worm.style.left = (event.clientX - worm.offsetWidth / 2) + 'px';
      worm.style.top = (event.clientY - worm.offsetHeight) + 'px';
    });
  </script>
- 👋 Hi, I’m FR1K676
- Languages I want to work in
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original-wordmark.svg" title="html" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" title="c++" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" title="js" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" title="python" width="40" height="40"/>&nbsp;
          
<!---
FR1K676/FR1K676 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

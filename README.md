# meow

https://www.google.com/

https://www.youtube.com

https://play.google.com

https://programmablesearchengine.google.com/controlpanel/all

javascript:(function()%7Bvar%20sidebar%20%3D%20document.createElement('div')%3Bsidebar.style.position%20%3D%20'fixed'%3Bsidebar.style.top%20%3D%20'0'%3Bsidebar.style.left%20%3D%20'0'%3Bsidebar.style.width%20%3D%20'250px'%3Bsidebar.style.height%20%3D%20'100%25'%3Bsidebar.style.backgroundColor%20%3D%20'%23333'%3Bsidebar.style.color%20%3D%20'%23fff'%3Bsidebar.style.zIndex%20%3D%20'1000'%3Bsidebar.style.padding%20%3D%20'10px'%3Bsidebar.style.boxShadow%20%3D%20'2px%200px%205px%20rgba(0%2C0%2C0%2C0.5)'%3Bvar%20closeBtn%20%3D%20document.createElement('button')%3BcloseBtn.innerHTML%20%3D%20'Close'%3BcloseBtn.style.display%20%3D%20'block'%3BcloseBtn.style.marginBottom%20%3D%20'10px'%3BcloseBtn.style.backgroundColor%20%3D%20'%23555'%3BcloseBtn.style.color%20%3D%20'%23fff'%3BcloseBtn.style.border%20%3D%20'none'%3BcloseBtn.style.padding%20%3D%20'10px'%3BcloseBtn.onclick%20%3D%20function()%7Bdocument.body.removeChild(sidebar)%3B%7D%3Bsidebar.appendChild(closeBtn)%3Bvar%20links%20%3D%20%5B'https%3A%2F%2Fgoogle.com'%2C%20'https%3A%2F%2Fgithub.com'%2C%20'https%3A%2F%2Fnews.ycombinator.com'%5D%3Blinks.forEach(function(link)%20%7Bvar%20a%20%3D%20document.createElement('a')%3Ba.href%20%3D%20link%3Ba.innerHTML%20%3D%20link%3Ba.style.display%20%3D%20'block'%3Ba.style.margin%20%3D%20'10px%200'%3Ba.style.color%20%3D%20'%23fff'%3Ba.style.textDecoration%20%3D%20'none'%3Bsidebar.appendChild(a)%3B%7D)%3Bdocument.body.appendChild(sidebar)%3B%7D)()
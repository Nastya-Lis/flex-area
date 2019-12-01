var isFall=false;
function ClickOnFlatIcon()
{
var meineMenu = document.getElementById("Main-menu-link");
    
    /*скопировали доч элементы meineMenu в copyMenu и добавили этот элемент в конце дочерних элементов header-inner*/
var Batya = document.getElementsByClassName("header-inner")[0];    
var copyMenu = meineMenu.cloneNode(true);
Batya.appendChild(copyMenu);
    
/* работаем с копией  meineMenu*/    
var ulMenu = copyMenu.getElementsByTagName("ul");  
var aMenu = ulMenu[0].getElementsByTagName("a");   
if(!isFall){ 
    
    copyMenu.style.display="block"; 
    
    ulMenu[0].style.listStyleType="none";
    for(let i =0; i < aMenu.length ; i++){
        
        aMenu[i].style.textDecoration="none";
        
        if(aMenu[i].parentElement!=null)
        aMenu[i].parentElement.style.backgroundColor="grey";
    }
   /* meineMenu.style.position =" absolute";
    meineMenu.style.background ="#333"; meineMenu.style.width = "100%";
    meineMenu.style.padding-right= 0;
    meineMenu.style.text-align = "left";
    meineMenu.style.left = 0;
    meineMenu.style.top = "100%";*/
    isFall =true;
}
   else
       {
           copyMenu.remove();
           isFall = false;
       }
}

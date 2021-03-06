<template>
  <div id="header">
      
        <img class="logo" src="@/assets/scool.png" alt="logo" />
        
<span style="font-size:30px;cursor:pointer" id="openNav">&#9776;</span>
        <ul id="mySidenav" class="sidenav nav">
          <a href="javascript:void(0)" class="closebtn" id="closeNav">&times;</a>
            <li>Become a Mentor</li>
            <li><button class="btn join-btn"> JOIN US</button></li>
        </ul>
        


  </div>
</template>

<script>

export default {
mounted(){

  

  document.getElementById("openNav").onclick =function() {
    document.getElementById("mySidenav").style.width = "110%";
  }

document.getElementById("closeNav").onclick =function() {
  document.getElementById("mySidenav").style.width = "0";

}
}

}
</script>

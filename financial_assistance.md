<div class = "navbar">
  <a href = "/"> Home </a>
  <a href = "/resources"> Resources </a>
</div>


<h2><strong>Financial Assistance</strong></h2>
<p> 
  This page consists of financial help resources. 
  <br>
  <a href="/lih">DHS LIHEAP</a>
  <br>
  <a href="/food">Food Stamps</a>
  <br>
  <a href="/housing">Housing Assistance</a>
  <br>
  <a href="/childcare">Child Care Assistance </a>
  
  
<div class = "navbar">
  <a href = "/"> Home </a>
  <a href = "/about"> About Me </a>
  <a href = "/projects"> Projects </a>
</div>
   
    
<style>
 .navbar{
  overflow: hidden;
  position: absolute;
  width: 100%;
  height: 6%;
  top: 0px;
  left: 0px;
  box-shadow: 0px 0px 8px 2px #000000;
  background-color: #155799;
  background-image: linear-gradient(120deg, #155799, #159957);
 }
  
.navbar a {
  float: left;
  font-size: 16px;
  color: #ffffff;
  text-decoration: none;
  text-align: center;
  padding: 16px 20px;
 }
 
 .navbar a:hover{
  background-color: #0c97b0;
  height: 100%;
  }
  .accordion {
  border: 2px solid #dce6f0;
  border-radius: 10px;
  margin: 5px 0;
}
.accordion-header {
  display: flex;
  padding: 16px;
  cursor: pointer;
  border-radius: 10px;
  background-color: #f3f6fa;
}
.accordion-title {
  flex: 1;
}
.accordion-icon {
  width: 16px;
  font-family: arial;
}
.accordion-content {
  padding: 16px;
  border-radius: 10px;
}
.accordion-content {
  display: none;
}
.accordion-header:hover {
  background-color: rgba(0, 0, 0, 0.1);
}
</style>
   
<script>

  const accordionHeaders = document.getElementsByClassName('accordion-header');
  const accordionContents = document.getElementsByClassName('accordion-content');
  const accordionIcons = document.getElementsByClassName('accordion-icon');


  for (let i = 0; i < accordionHeaders.length; i++) {
    accordionHeaders[i].addEventListener('click', () => {
      accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
      accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '▼' : '◀';
    });
  }
  
</script>


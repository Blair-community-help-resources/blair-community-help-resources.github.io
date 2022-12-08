<div class = "navbar">
  <a href = "/"> Home </a>
  <a href = "/about"> About Me </a>
  <a href = "/resources"> Resources </a>
</div>


<h2><strong>Altoona Food Bank</strong></h2>
<p> 
  Information about the Altoona Food Bank 
</p>
 <p>
  <ul>
    <li>Address 2318 Branch Ave, Altoona, PA, 16602</li>
  <li>Hours: MWF 9:15AM - 12:00PM</li>
  <li>Invdividuals can expect to recieve at least one box of food containing non-perishable items such as canned goods, bakery items, etc</li>
    <li> Donations are recieved from individuals within the community and local businesses </li>
    <li>Staff consists of volunteers dedicated to helping the local community.  </li>
   </ul>
  </p>
   <br>   
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

   

<div class = "navbar">
  <a href = "/"> Home </a>
  <a href = "/resources"> Resources </a>
</div>


<h2><strong>Other</strong></h2>
<p> 
  The following is a interactable list of additional assistance available to low-income individuals/families in the Blair County area. 
</p>
   <div class="accordion">
     <div class="accordion-header">
        <div class="accordion-title">Other Assistance:</div>
        <span class="accordion-icon">◀</span>
      </div>
      <div class="accordion-content">
        <ul>
          <li><a href="https://www.centerforcommunityaction.org/our-departments/employment-and-training/hsbg-educational-services">EARN Program</a></li>
          <li>AASD Adult Education Program</li>
          <li><a href="https://www.blaircap.org/services/">Education Services offered by the Blair CAP</a></li>
          <li><a href="https://www.pacareerlink.pa.gov/jponline/">CareerLink</a></li>
          <li><a href="https://www.dhs.pa.gov/Services/Assistance/Pages/Medical-Assistance.aspx">PA DOH low-income medical insurance</a></li>
        </ul>
      </div>
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

  

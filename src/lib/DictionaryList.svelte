<div class="container horizontal_list">  
    
    <div class="border horizontal_list_item">Item</div>
    <div class="border horizontal_list_item">Item</div>
    <div class="border horizontal_list_item">Item</div>
    <div class="border horizontal_list_item">Item</div>
    <div class="border horizontal_list_item">Item</div>
</div>  

<style> 
    .container {
        grid-area: 4 / 1 / 5 / 3;
        margin: .25rem 0;
    }  
    
    

  .horizontal_list {
      display: flex;
      overflow-x: scroll;
  }

  .horizontal_list_item {
      flex: 0 0 8rem;
      height: 4rem;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0 .25rem;
  }
 </style> 

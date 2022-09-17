header{
    height: 100px;
    width: 100%;
    margin: auto;
    background: rgb(65, 78, 107);
    color: white;
    padding: 20px;
    margin-bottom: 10px;
    text-align: center;
  
  }
  body{
  
    background-color: lightgray;
  }
 
  
.container{
    display: flex;
    justify-content: space-between;
    color:rgb(65, 78, 107);
    margin-top: 30px;
    
  }
  .nor, .ty, .tr{
    text-align: center;
  }
  .flagtr{
    width: 300px;
    height: 200px;
  }
  .flag {
    position: relative;
    width: 300px;
    height: 190px;
    background-color: #cd3d2e;
    
  }
  .flag .blue {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 1;
  }
  
  .flag .blue:before, .flag .blue:after {
    position: absolute;
    content: '';
    background-color: #34495e;
  }
  .flag .blue:before {
    bottom: 0;
    left: 95px;
    width: 20px;
    height: 100%;
  }
  .flag .blue:after {
    top: 50%;
    right: 0;
    width: 100%;
    height: 20px;
    transform: translateY(-50%);
  }
  .flag .white {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 0;
  }
  .flag .white:before, .flag .white:after {
    position: absolute;
    content: '';
    background-color: #fff;
  }
  .flag .white:before {
    bottom: 0;
    left: 85px;
    width: 40px;
    height: 100%;
  }
  .flag .white:after {
    top: 50%;
    left: 0;
    width: 100%;
    height: 40px;
    transform: translateY(-50%);
  }
  .tysk {
    height: 190px;
    width: 300px;
    overflow: hidden;
  
  }
  .stripe {
    display: block;
    width: 100%;
    height: 33.3%;
  }
  .black {
    background-color: #000000;
  }
  .red {
    background-color: #FF0000;
  }
  .gold{
    background-color: #FFCC00;
  }

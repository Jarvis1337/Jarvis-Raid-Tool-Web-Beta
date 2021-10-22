.logout{
  display: inline-flex;
}

.logout .icon{
  margin: 0 20px;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  position: relative;
  z-index: 2;
  transition: all 0.4s cubic-bezier(0.68,-0.55,0.265,1.55);
}

.logout .icon span{
  position: relative;
  height: 40px;
  width: 40px;
  display: block;
  background: #fff;
  text-align: center;
  border-radius: 50%;
  z-index: 2;
  box-shadow: 0 10px 10px rgba(0,0,0,0.1);
}




.logout .icon span i{
  font-size: 27px;
  padding-right: 2px;
  line-height: 40px;
  padding-bottom: 15pc;
}

.logout .icon:hover span{
  color: rgb(255, 255, 255);
}

.logout .icon .tooltip{
  position: absolute;
  top: 0px;
  background: white;
  color: #fff;
  font-size: 20px;
  padding: 10px 18px;
  border-radius: 25px;
  box-shadow: 0 10px 10px rgba(0,0,0,0.1);
  opacity: 0;
  pointer-events: none;
  transition: all 0.4s cubic-bezier(0.68,-0.55,0.265,1.55);
}

.logout .icon:hover .tooltip{
  top: -70px;
  opacity: 1;
  pointer-events: auto;
}

.logout .icon .tooltip:before{
  position: absolute;
  content: "";
  height: 15px;
  width: 15px;
  background: linear-gradient(to bottom right, #00CCFF, #0000Ff);  change  
  bottom: -8px;
  left: 50%;
  transform: translatex(-50%) rotate(45deg);
}

.logout .icon:hover span,
.logout .icon:hover .tooltip{
  text-shadow: 0px -1px 0px rgba(0,0,0,0.4);
}

.logout .icon:hover span,
.logout .icon:hover .tooltip,
.logout .icon:hover .tooltip:before{
  background: linear-gradient(to bottom right, #00CCFF, #0000Ff);  change 
} 
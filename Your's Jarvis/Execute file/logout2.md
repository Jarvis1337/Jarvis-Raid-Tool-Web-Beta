.sidebar .nav-links h1{
  position: relative;
  list-style: none;
  transition: all 0.4s ease;
}
.sidebar .nav-links h1:hover{
  background: #1d1b31;
}
.sidebar .nav-links h1 .iocn-link{
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.sidebar.close .nav-links h1 .iocn-link{
  display: block
}
.sidebar .nav-links h1 i{
  height: 50px;
  min-width: 78px;
  text-align: center;
  line-height: 50px;
  color: #fff;
  font-size: 20px;
  cursor: pointer;
  transition: all 0.3s ease;
}
.sidebar .nav-links h1.showMenu i.arrow{
  transform: rotate(-180deg);
}
.sidebar.close .nav-links i.arrow{
  display: none;
}
.sidebar .nav-links h1 a{
  display: flex;
  align-items: center;
  text-decoration: none;
}
.sidebar .nav-links h1 a .link_name{
  font-size: 18px;
  font-weight: 400;
  color: #fff;
  transition: all 0.4s ease;
}
.sidebar.close .nav-links h1 a .link_name{
  opacity: 0;
  pointer-events: none;
}
.sidebar .nav-links h1 .sub-menu{
  padding: 6px 6px 14px 80px;
  margin-top: -10px;
  background: #1d1b31;
  display: none;
}
.sidebar .nav-links h1.showMenu .sub-menu{
  display: block;
}
.sidebar .nav-links h1 .sub-menu a{
  color: #fff;
  font-size: 15px;
  padding: 5px 0;
  white-space: nowrap;
  opacity: 0.6;
  transition: all 0.3s ease;
}
.sidebar .nav-links h1 .sub-menu a:hover{
  opacity: 1;
}
.sidebar.close .nav-links h1 .sub-menu{
  position: absolute;
  left: 100%;
  top: -10px;
  margin-top: 0;
  padding: 10px 20px;
  border-radius: 0 6px 6px 0;
  opacity: 0;
  display: block;
  pointer-events: none;
  transition: 0s;
}
.sidebar.close .nav-links h1:hover .sub-menu{
  top: 0;
  opacity: 1;
  pointer-events: auto;
  transition: all 0.4s ease;
}
.sidebar .nav-links h1 .sub-menu .link_name{
  display: none;
}
.sidebar.close .nav-links h1 .sub-menu .link_name{
  font-size: 18px;
  opacity: 1;
  display: block;
}
.sidebar .nav-links h1 .sub-menu.blank{
  opacity: 1;
  pointer-events: auto;
  padding: 3px 20px 6px 16px;
  opacity: 0;
  pointer-events: none;
}
.sidebar .nav-links h1:hover .sub-menu.blank{
  top: 50%;
  transform: translateY(-50%);
}
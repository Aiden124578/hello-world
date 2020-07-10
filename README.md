.profile{
    /* border: 1px solid red; */
    display: flex;
    justify-content: flex-end;
    align-items: center;
    width: 100%;
    height: 73px;
    background-color: #fff;
    text-align: center;
    padding-right: 29px;
}
.nomal{
    display: flex;
    align-items: center;
}
.profile_photo{
    /* border: 1px solid red; */
}
.font{
    /* border: 1px solid red; */
    color: #242424FF;
    padding-left: 10px;
}
em{
    font-style:normal;
    padding-left: 10px;
}
.end{
    color: #4D65F3FF;
    padding-left: 10px;
}
.pos{
    display: inline-block;
    height: 73px;
    line-height: 73px;
}
/* 内容 */
.content{
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    position: relative;
    top: 0;
}
.nav{
    width: 161px;
    /* 561px */
    height: 600px;
    background-color: #3A3F49FF;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding-top: 20px;
}
.nav ul li{
    /* border: 1px solid red; */
    padding-right: 10%;
    list-style: none;
    height: 50px;
    /* line-height: 50px; */
}
.nav ul li img{
    padding-right: 8%;
}
.nav ul li a{
    /* padding-left: 10px; */
    color: #fff;
    font-family:"PingFang SC";
}
.nav ul li a:hover{
    color: #4D65F3FF;
}
.nav ul li section{
    color: #fff;
}
.nav .active{
    color: #4D65F3FF;
}

.main_content{
    /* border: 1px solid red; */
    background-color:#F4F4F4FF;
    /* display: flex; */
    /* justify-content: space-between; */
    flex: 1;
    z-index: 9;
}
.show_content{
    width: 85%;
    height: 65%;
    position: absolute;
    top: 30%;
    left: 187px;
    background-color: #fff;
    /* flex-direction: column; */
    z-index: 999;
}
.phtot_content{
    display: flex;
}
.data{
    margin-top: 5px;
    margin-bottom: 20px;
    margin-left: 20px;
    margin-right: 18px;
    width:300px;
    height:150px;
}
.data_1{
    flex: 1;
    background:linear-gradient(90deg,rgba(234,104,124,1),rgba(238,139,102,1));
    border-radius:8px;
}
.data_2{
    flex: 1;
    background:linear-gradient(90deg,rgba(62,164,247,1),rgba(115,123,247,1));
    border-radius:8px;
}
.data_3{
    flex: 1;
    background:linear-gradient(90deg,rgba(111,95,255,1),rgba(216,97,255,1));
    border-radius:8px;
}
.photo_1{
    padding-left: 40px;
    padding-top: 13px;
}
.data_1 span,.data_2 span,.data_3 span{
    padding-left: 5px;
    color: #fff;
} 
.data_1 h1,.data_2 h1,.data_3 h1{
    padding-top: 13px;
    padding-left: 40px;
    color: #fff;
}
.img_order{
    padding-top: 13px;
    padding-left: 40px;
}
.data_1_left{
    display: flex;
    justify-content: space-between;
}
.reduce{
    margin-top: 5px;
    width: 80%;
    height: 100%;
}

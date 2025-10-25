#goit-markup-hw-06

Питання:
1) У вікні Modal (mobile) відступ від кнопки вийшов згідно макету, але на переході на tablet, desktop з'являється додатковий нижній відступ, котрий неможу ніяк знайти і анулювати. Що це може бути?

320px - mobile 
768px - tablet 
1158px - desktop

@media only screen and (min-width: 768px){}
@media only screen and (min-width: 1158px){}

FSon-124 Homework-6 by Illia Kumpan

    --iris: #4d5ae5;
    --ocean: #404bbf;
    --navy-blue: #2e2f42;
    --green: #31d0aa;
    --slate: #434455;
    --light-slate: #8e8f99;
    --cornflower: #e7e9fc;
    --cloud: #f4f4fd;
    --navy-blue-modal: rgba(46, 47, 66, 0.4);
    --grey: rgba(46, 47, 66, 0.7);
    --white: #fff;
    --dairy: #fcfcfc;

Raleway - 700
font-family: "Raleway", sans-serif;
font-optical-sizing: auto;
font-weight: 700;
font-style: normal;

Roboto - 400, 500, 700
font-family: "Roboto", sans-serif;
font-optical-sizing: auto;
font-weight: 400;
font-style: normal;



git add .
git commit -m hw-06
git push -u origin main

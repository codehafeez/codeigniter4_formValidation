# Codeigniter4 Simple Example - Form Validation

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.codehafeez.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/codehafeez/)

[![whatsapp](https://img.shields.io/badge/whatsapp-GREEN?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=923123349398)



```bash
CMD RUN => composer create-project codeigniter4/appstarter formValidation
CMD RUN => cd formValidation


CMD RUN => php spark migrate:create create_users_table
CMD RUN => php spark migrate


CMD RUN => php spark make:model FormModel
CMD RUN => php spark make:controller FormController


Update File => app/Config/Routes.php
  $routes->get('/', 'FormController::index');
  $routes->match(['get', 'post'], 'FormController/store', 'FormController::store');


CMD RUN => php spark serve
```    

## Screenshots
![](https://raw.githubusercontent.com/codehafeez/codeigniter4_formValidation/main/Screenshots/Output-01.png)
![](https://raw.githubusercontent.com/codehafeez/codeigniter4_formValidation/main/Screenshots/Output-02.png)


## 🔗 www.codehafeez.com

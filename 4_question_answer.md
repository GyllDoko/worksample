
> How to use singular and plural properly in rails ?

According to rails naming convention

`For generators`
- [ ] we use singular for model names because models represent a single instance
- [ ] we use plural for controller names because they control many routes
- [ ] we use singular for ressource names because this commands is use to create a lot of MVC framework. So the name you pass become the model name ad rails pluralize the rest
- [ ] we use plural for migrations names because tables names are plural to.

`For routes`
- [ ] here, if you are using 'resources' keyword, you should use plural for routes names

`For views`

- [ ] Views directories are plural because there are many directories
- [ ] Views files however are singular because they render a single view


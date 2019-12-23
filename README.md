# angular-setup-scss-ngMaterial
  Angular setup with scss and angular material
# create project setup using angular with scss
   ng new #project-name# --style=scss
# create a custom material module
Angular Material module will be a central place where you can include all material module:- <br>
 Steps:
 1. ng generate module app-material   --- to add app material module
 2. Import app material module in the app module.
    #
    import { AppMaterialModule } from './app-material/app-material.module';
...
@NgModule({
  ...
  imports: [
    BrowserModule,
    BrowserAnimationsModule,
    AppMaterialModule
  ],
  ...
export class AppModule { }
    #
 3.
 
   

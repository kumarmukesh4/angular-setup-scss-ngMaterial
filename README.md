# angular-setup-scss-ngMaterial
  Angular setup with scss and angular material
# create project setup using angular with scss
   ng new #project-name# --style=scss
# create a custom material module
Angular Material module will be a central place where you can include all material module:- <br />
 Steps:
 1. First add angular material into your project by running below commonad <br />
    ng add @angular/material <br /><br />
 2. create and add material module <br />
    ng generate module app-material  <br /><br /> 
 3. Import app material module in the app module. <br />
    `import { AppMaterialModule } from './app-material/app-material.module';
     imports: [
    BrowserModule,
    BrowserAnimationsModule,
    AppMaterialModule
    ], `<br /><br />
 4. Import material component module in the app material module. <br />
           `
            import { NgModule } from '@angular/core';  
            import { CommonModule } from '@angular/common';   
            import { MatInputModule, MatButtonModule } from '@angular/material';  
          @NgModule({  
            imports: [ 
              CommonModule, 
              MatInputModule,  
              MatButtonModule  
            ],  
            exports: [  
              MatInputModule,  
              MatButtonModule  
            ]  
          }) 
          export class AppMaterialModule { } <br>
            `
 4.  
 
   

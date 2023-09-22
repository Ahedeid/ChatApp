## Design

 ![Frame 24](https://github.com/Ahedeid/ChatApp/assets/69312571/8c1ace5c-47fc-4694-82de-c193b7c17403)
![Frame 25](https://github.com/Ahedeid/ChatApp/assets/69312571/c9e5c16c-b991-49fe-a9ef-0ec30ec81667)
![Frame 26](https://github.com/Ahedeid/ChatApp/assets/69312571/53e4a10d-1e7c-4ae0-92a3-ecffd796239b)


# ChatApp

Folder Structure 
By Feature inside every features will be MVC.



```
 |-lib|
     |     
     | Registration | models -> All models that conceren with this feature 
                    | screens -> If the feature has many sub features you can divide it with sub folder if needed
                    | providers -> All providers that needed in this feature 
                    | repositories -> For every provider should have his repo
                    | widgets -> Just the widget that concern with this feature 
```

## Usage
If you wanna access resources manger:

Real time by Sokcet Io

```dart
# colors
ColorManager.primary;

# images
ImageAssets.splashLogoPng;
SVGAssets.homeSvg;
IconAssets.arrowRight;

# fontWeightManager
FontWeightManager.black;

# text Strings
AppString.bankWithdraw;
```



# For navigation the project built based on OnGenerateRoute:


```dart
# pushNamed
sl<NavigationService>().navigateTo(Routes.home);

# pushNamedAndRemoveUntil
sl<NavigationService>().navigateToAndRemove(Routes.home);

# pop;
sl<NavigationService>().pop();
```

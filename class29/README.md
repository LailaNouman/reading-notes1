# Class-29:

### Custom User Model:
Django ships with a built-in User model for authentication. However, for a real-world project, the official Django documentation highly recommends using a custom user model instead. This provides far more flexibility.
There are two modern ways to create a custom user model in Django: AbstractUser and AbstractBaseUser. In both cases we can subclass them to extend existing functionality.

#### Creating our initial custom user model requires four steps:
- update django_project/settings.py: we'll add the accounts app and use the AUTH_USER_MODEL config to tell Django to use our new custom user model in place of the built-in User model. Within INSTALLED_APPS add accounts at the bottom. Then at the bottom of the entire file, add the AUTH_USER_MODEL config.
Now update accounts/models.py with a new User model.
- create a new CustomUser model: Add a new User model.
- create new UserCreation and UserChangeForm: Create a new file in the app called forms.py and add two classe one CustomUserCreation and the other is CustomUserChangeForm
- update the admin: Update the admin.py with the new CustomUser model.

And we're done! We can now run makemigrations and migrate for the first time to create a new database that uses the custom user model.



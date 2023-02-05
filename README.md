# Laravel-Tips
Laravel Tips: A resource of useful Laravel development tips and tricks. Keep up with the newest trends and hone your Laravel development abilities. This repository is likely to offer something for you, whether you're a novice or an experienced developer!

By [@deesynertz](https://github.com/deesynertz)


# Database Block

**check which database your laravel project connect to**

  > in blade file

  ```bash
 <?php
    try {
        \DB::connection()->getPDO();
        echo \DB::connection()->getDatabaseName();
        } catch (\Exception $e) {
        echo 'None';
    }
?>
  ```

  > In Controller |Service | Trait | Helper files

  ```bash
  try {
      \DB::connection()->getPDO();
      echo \DB::connection()->getDatabaseName();
      } catch (\Exception $e) {
      echo 'None';
  }
  ```


### I welcome any contribution if you a have any tips you think we should know

### LISENCE AND CONTACT

[![General badge](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/deesynertz/how_to_create_rep)

[![General badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](MailTo:deesynertz@gmail.com)

[![General badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deogratias-alison/)


[@deesynertz](https://github.com/deesynertz) Enjoy using Github for best software version control - it's ready to merge!


![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

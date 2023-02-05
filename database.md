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

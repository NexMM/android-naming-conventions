###1. Package Structure

  src
    `com.client.app`            - contain Application class only
    `com.client.app.views`      - contain all activities
    `com.client.app.fragments`  - contain all fragments
    `com.client.app.webservice` - contain all web services
    `com.client.app.adapters`   - contain all adapters
    `com.client.app.db`         - contain all db related classes
    `com.client.app.models`     - contain all models
    `com.client.app.utils`      - contain utility/misc classes
    `com.client.app.widgets`    - contain extended/custom views
    `com.client.app.services`   - contain all services
    `com.client.app.animation`  - contain all animations

###2. Naming convention for Xml files

  * `activity_<ACTIVITY NAME>.xml` - for all activities
  * `dialog_<DIALOG NAME>.xml`     - for all custom dialogs
  * `row_<LIST_NAME>.xml`          - for custom row for listview
  * `fragment_<FRAGMENT_NAME>.xml` - for all fragments

###3. Naming convention for component/widget in xml files.

  * all component for x activity must be start with activity name
  * all component should have prefix or short name like btn for button
  * For example,name for login activity component should be like following.

    * activity_login_btn_login
    * activity_login_et_username
    * activity_login_et_password
  * Short name of major components

    * Button - btn
    * EditText - et
    * TextView - tv
    * Checkbox - chk
    * RadioButton - rb
    * ToggleButton - tb
    * Spinner - spn
    * Menu - mnu
    * ListView - lv
    * GalleryView - gv
    * LinearLayout -ll
    * RelativeLayout - rl

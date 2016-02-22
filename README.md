# AndroidNamedGuidance
Android命名规范

//命名规范
1.Java类命名
    Activity:以Activity作为后缀,如PersonActivity(当分模块时,应当使用包级的限制,而不是体现在Activity名称上)
    Adapter:以Adapter作为后缀,如PersonAdapter.Adapter可以不分模块
    实体:大多以Entity作为后缀.如PersonEntity
2.资源文件命名
    Activity或Fragment布局文件:activity(fragment)+模块名+逻辑名称,如activity_person_addcustomer.xml
    列表中item布局文件:item+模块名+逻辑名称,如item_person_userlist.xml
    dialog布局文件:dialog+模块名+逻辑名称,如dialog_person_hint.xml
    图片资源文件:ic+模块名+逻辑名称或img+模块名+逻辑名称,如ic_person_setting.png  img_person_bg.png
    图片xml文件:类型+模块名称+逻辑名称,如selector_person_item_bg.xml
3.Java类中控件对象命名
    控件对象缩写+逻辑名称,如tvUserName,btnLogin
4.布局文件中控件id名称
    控件对象缩写+逻辑名称,如tv_username,btn_login
5.字符串资源命名
    页面+使用控件+描述,如special_sale_hint_love,special_sale_tv_love,
                       special_sale_btn_love,special_sale_toast_love

    公共字符串命名规范:public + 使用控件 + 描述,如public_tv_close,public_loading_love
6.常量命名
    只包含字母和下划线,字母全部大写,如NET_REQUEST_SUCCESS

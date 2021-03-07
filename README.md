# Myblog

## 1.新建项目

输入命令：`django-admin startproject blog`

在当前文件夹自动创建了`blog`项目

## 2.连接数据库

我使用`pymydql`库连接数据库

在`setting.py`文件中修改数据库配置

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'HOST':'127.0.0.1',
        'PORT': 3306,
        'USER': '****',
        'PASSWORD': '****',
        'NAME': 'myblog',
        # 'NAME': BASE_DIR / 'db.sqlite3',
    }
}
```


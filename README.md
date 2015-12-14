# yii-yashare
Виджет шаринга в социальные сети для Yii (Блок Поделиться от Яндекса)

## Подключение:
Скопируйте файл YaShare.php в нужную вам директорию. Например это protected/extensions, тогда подключение будет выглядеть так:

```
$this->widget('application.extensions.YaShare', [
  'services' => param('yaShareServices', 'vkontakte,twitter,facebook,gplus,odnoklassniki,moimir'),
  'iconLimit' => 3,
  'title' => 'Поделиться в соцсетях',
]);
```

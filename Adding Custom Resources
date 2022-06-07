# Adding Custom Resources / 添加自定义资源包
Jonathan Ho edited this page on 27 Jul 2021 · 3 revisions
Jonathan Ho 编辑于 2021.7.27 3个历史版本

User-created content can be added to the Minecraft Transit Railway mod via resource packs.

Currently, players can add the following:

- Texture variants for existing trains
- New textures or text for railway signs

It is highly recommended to be familiar with creating a resource pack before proceeding with this guide.

用户自定义的内容可以通过资源包添加到我的世界铁路模组中。目前，玩家可以添加以下内容：

- 现有列车的变种纹理（译者注：”texture”的官方简体中文标准译名已由“材质”更改为“纹理”，故以下均按标准译名翻译。）
- 新的铁路标志纹理或文本

## Resource Pack Format / 资源包格式

The file mtr_custom_resources.json is the main file that will get loaded. This file defines custom content for the mod to register. It must be placed under the mtr namespace; in other words, it must have the file path of assets/mtr/mtr_custom_resources.json.

mtr_custom_resources.json文件是模组所加载的主要文件。这个文件明确了模组要注册的自定义内容。它必须放在mtr命名空间下，换言之，它必须放在assets/mtr/mtr_custom_resources.json路径下。

## Adding Texture Variants for Existing Trains / 添加现有列车的变种纹理

To add texture variants, the custom_trains JSON object should be added to mtr_custom_resouces.json. Each JSON object under custom_trains, representing a texture variant for a train, should have a unique key and serveral required entries.

要想添加变种纹理，custom_trains JSON文件应该添加到mtr_custom_resouces.json文件。每个custom_trains下的JSON文件代表列车的一个变种纹理，应该有一个独特的标签和几个需要的条目。

An example is shown below.

下面是一个示例。

```
{
  "custom_trains": {
    "my_custom_train": {
      "name": "My Custom SP1900 Train",
      "color": "FEC5E5",
      "base_train_type": "sp1900",
      "texture_id": "mtr:custom_directory/custom_sp1900.png"
    }
  }
}
```

## Adding New Railway Sign Textures or Text / 添加新的铁路标志纹理或文本

To add new railway signs textures or text, the custom_signs JSON object should be added to mtr_custom_resouces.json. Each JSON object under custom_signs, representing a new sign, should have a unique key and serveral required entries.

要想添加新的铁路标志纹理或文本，custom_signs JSON文件应该添加到mtr_custom_resouces.json文件。每个custom_signs下的JSON文件代表一个新的标志，应该有一个独特的标签和几个需要的条目。

An example is shown below.

下面是一个示例。

```
{
  "custom_signs": {
    "my_custom_sign": {
      "texture_id": "mtr:custom_directory/custom_sign.png",
      "flip_texture": false,
      "custom_text": "你好|Hello",
      "flip_custom_text": false,
      "small": true,
      "background_color": "1167B1"
    }
  }
}
```

## Verifying the Resource Pack / 校验资源包

Use a JSON validator to check for any syntax errors of the JSON files.

使用JSON校验器检查JSON文件中的语法错误。

The resource pack (zip file) can be installed either clientside or as a server resource pack. If installed as a server resource pack, all players joining the server will be able to see the new additions after accepting the server resource pack.

Zip格式的资源包可以在服务端安装或作为服务器资源包安装。如果作为服务器资源包安装，所有加入服务器的玩家在接受服务器资源包后均可看到新添加的内容。

Download the example resource pack to see a full example and to test out the functionality.

下载这个示例资源包可以查看一个完整的示例或检验这个功能。



翻译、校对：木新同学，保留对译文的所有权利。转载请联系译者。

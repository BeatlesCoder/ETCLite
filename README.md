# ETCLite
auto using etc+alpha texture in android platform,automatic handler for you!

------------------------------------CN-------------------------------------------

NOTE:ʹ�õ���shader��ע�⣬�Ƿ񸲸���֮ǰNGUI��shader
1��ʹ�����Editor/ETCTexturePostprocessor.cs�ļ����޸� ADD TARGET FOLDER TO AUTO USE ETC + ALPHA ������ļ�Ŀ¼�Զ�������Ϣ
2���л�ƽ̨Android��iOS���Զ������õ�Ŀ¼������ͼת��
3���ڹ�����TextureSetting/ETC/�����ֶ�ת����ȫ�����á�ѡ��Ŀ¼ת����
4����Editor/ETCTexturePostprocessor.cs��EditorSelectedFolderWindow�п�������һЩshader�б��Թ�ѡ��
5���ֶ�Ŀ¼ת����������DontChangedѡ�ʹ��RGBA32�����ͼ

version 1.0
- FIX:�Զ����ô����б�߶Ȳ���
- FIX:���Ŀ¼ͼƬ���ർ�µ��ڴ汩������

------------------------------------ENG-------------------------------------------
NOTE:care for importing this package,sure to not convert the NGUI orignal shaders.
1��you can modify "ADD TARGET FOLDER TO AUTO USE ETC + ALPHA" under Editor/ETCTexturePostprocessor.cs��add automatic folder.
2��after change the Editor Platform to Android or iOS will trigger automatic handler.
3��you can click topbar button:TextureSetting/ETC/ change selection folder by yourself.
4��you can modify "EditorSelectedFolderWindow" under Editor/ETCTexturePostprocessor.cs for new shader list!
5��in editor windows you can toggle the "DontChange" to reconvert use RGBA32.

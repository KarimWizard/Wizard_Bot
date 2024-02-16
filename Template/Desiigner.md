<div align="center">
    <h1> Шаблон «Desiigner» </h1>
    <img src="../MediaImg/MediaVK-.svg" height="30"/>
    <img src="../MediaImg/MediaTG-.svg" height="30"/>
    <img src="../MediaImg/MediaDC-.svg" height="30"/>
    <img src="../MediaImg/MediaOK-.svg" height="30"/>
    <br>
    <kbd><a href="../ReadMe.md">< Вернуться к списку шаблонов ></a></kbd>
    <hr>
</div>

<div align="left">
    Шаблон бота, использующего нейросеть для исполнения различных задач. Например, создания изображений (или qr-кодов) по запросу пользователя или
    рисования изображений для публикации в соц.сетях. Может использовать модели: <code>LeonardoAI</code> или <code>QuickqrArt</code>.
</div>

<br>

<pre lang="Python">
    from KarakurtAPI.OpenAPIs import Medianet
    
    Key = "0123456789:AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA"
    Bot = Medianet.BotsTG(Key)
    
    while True:
        for Event in Bot.getEvents():
            ...
</pre>

<div align="center">
    <br>
    <hr>
    <samp>KarakurtAPI</samp>
</div>
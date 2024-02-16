<div align="center">
    <h1> Шаблон «KnowItAll» </h1>
    <img src="../MediaImg/MediaVK-.svg" height="30"/>
    <img src="../MediaImg/MediaTG-.svg" height="30"/>
    <img src="../MediaImg/MediaDC-.svg" height="30"/>
    <img src="../MediaImg/MediaOK-.svg" height="30"/>
    <br>
    <kbd><a href="../ReadMe.md">< Вернуться к списку шаблонов ></a></kbd>
    <hr>
</div>

<div align="left">
    Шаблон бота, использующего нейросеть для исполнения различных задач. Например, формирование ответа на вопрос пользователя или написание текста
    для публикации в соц.сетях. Может использовать модели: <code>ChatGPT</code>, <code>YandGPT</code> или <code>SberGPT</code>.
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
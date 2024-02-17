<div align="center">
    <h1> Шаблон «InterQuiz» </h1>
    <img src="../MediaImg/MediaVK-.svg" height="30"/>
    <img src="../MediaImg/MediaTG+.svg" height="30"/>
    <img src="../MediaImg/MediaDC-.svg" height="30"/>
    <img src="../MediaImg/MediaOK-.svg" height="30"/>
    <br>
    <kbd><a href="../ReadMe.md">< Вернуться к списку шаблонов ></a></kbd>
    <hr>
</div>

<div align="left">
    Шаблон бота, помогающего провести опрос пользователей не выходя из удобного мессенджера. Предназначен замены онлайн-квизов в рамках продвижения
    услуг в соц.сетях. Может содержать в себе выбор ответа из предложенных, либо получение ответа в свободной форме.
</div>

<div align="center">
    <br>
</div>

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
</div>

<div align="center">
    <samp>KarakurtAPI</samp>
</div>
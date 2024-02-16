<div align="center">
    <h1> Шаблон «WebMarket» </h1>
    <img src="../MediaImg/MediaVK-.svg" height="30"/>
    <img src="../MediaImg/MediaTG-.svg" height="30"/>
    <img src="../MediaImg/MediaDC-.svg" height="30"/>
    <img src="../MediaImg/MediaOK-.svg" height="30"/>
    <br>
    <kbd><a href="../ReadMe.md">< Вернуться к списку шаблонов ></a></kbd>
    <hr>
</div>

<div align="left">
    Шаблон веб-маркета в социальных сетях, предназначен для замены/дополнения онлайн магазинов. Может иметь как простое меню с перелистыванием
    товаров, так и сложные структуры из разделов и выбора количества, желаемого для приобретения.
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
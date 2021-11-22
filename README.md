# FOSS-Android
[Lista Original]:(https://github.com/theel0ja/foss-android/edit/master/README.md)
Traduzido e adaptado por [mim] (https://github.com/higorslva)

Lista de software [livres e códigos abertos](https://pt.wikipedia.org/wiki/Software_livre_e_de_c%C3%B3digo_aberto) alternativos para softwares proprietarios no Android.

Sinta-se livre para [contribuir](https://github.com/theel0ja/foss-android/edit/master/README.md), [forkear](https://github.com/theel0ja/foss-android/fork) e favoritar essa lista. :)

## Sistema Operacional

|Proprietary app|FOSS App|
|---------------|--------|
|Android|[Fork Lineage OS com MicroG](https://lineage.microg.org/) (se disponível), [LineageOS](https://lineageos.org/)|
|[Google Play services](https://pt.wikipedia.org/wiki/Google_Play_Services)|[microG](https://microg.org/)|
|[Google Play Store](https://pt.wikipedia.org/wiki/Google_Play)|[F-Droid](https://f-droid.org/pt/) (Apenas apps FOSS), [Aurora Store](https://f-droid.org/en/packages/com.dragons.aurora/) ou [Yalp Store](https://f-droid.org/packages/com.github.yeriomin.yalpstore/) (Clientes gratuitos para a Play Store)|

## Deve ter esses aplicativos

* [AdAway](https://f-droid.org/packages/org.adaway/) (requer acesso root, eu recomendo adicionar `https://energized.pro/blu` como source) ou [Blokada](https://blokada.org/) (sem root, [grupo no telegram](https://t.me/blokadachat)) para bloquear propagandas e outros rastreadores.
* [Copy to Clipboard](https://f-droid.org/en/packages/se.johanhil.clipboard/) ou [Share to Clipboard](https://f-droid.org/en/packages/com.tengu.sharetoclipboard/)

## Básico

|Propósito do app|App proprietário|App código aberto|
|------------------|---------------|--------|
|Mapas|[Google Maps](https://play.google.com/store/apps/details?id=com.google.android.apps.maps&hl=en)|[OsmAnd](https://f-droid.org/packages/net.osmand.plus/), [F-Droid Maps](https://f-droid.org/en/packages/com.github.axet.maps/) (baseado em [MAPS.ME](https://maps.me/))|
|Sincronizar fotos|[Google Photos](https://play.google.com/store/apps/details?id=com.google.android.apps.photos&hl=en)|[Nextcloud](https://nextcloud.com/) Upload instantâneo|
|Navegador|[Chrome](https://play.google.com/store/apps/details?id=com.android.chrome), [Firefox](https://play.google.com/store/apps/details?id=org.mozilla.firefox) (possui algumas bibliotecas do Chromecast)|[Fennec F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/) (Fork do Firefox), [Waterfox](https://play.google.com/store/apps/details?id=org.waterfoxproject.waterfox) (Fork do Firefox, não disponível no F-Droid), Tor Browser para Android, [Bromite](https://www.bromite.org/) (Fork do Chromium, com bloqueador de propaganda funcionando bem)|
|Sincronizar contatos|[Google Contacts](https://en.wikipedia.org/wiki/Google_Contacts)|Servidor Nextcloud com [DAVdroid](https://f-droid.org/en/packages/at.bitfire.davdroid/) ([guia](https://www.davdroid.com/tested-with/nextcloud/))|
|App de SMS|[Android Messages](https://play.google.com/store/apps/details?id=com.google.android.apps.messaging&hl=en), padrão do seu telefone|[Silence](https://f-droid.org/en/packages/org.smssecure.smssecure/), [QKSMS](https://f-droid.org/packages/com.moez.QKSMS/), [Signal](https://signal.org/android/apk/) ([código aberto](https://github.com/signalapp/Signal-Android), APK proprietário, com dependencias da Google!)|
|Teclado|[Gboard](https://play.google.com/store/apps/details?id=com.google.android.inputmethod.latin), [SwiftKey](https://play.google.com/store/apps/details?id=com.touchtype.swiftkey), Teclado incluso na sua ROM|[Simple Keyboard](https://f-droid.org/en/packages/rkr.simplekeyboard.inputmethod/), [AnySoftKeyboard](https://anysoftkeyboard.github.io/), Teclado AOSP (incluído na Lineage OS)|
|App de início (Launcher)||[Lawnchair](https://f-droid.org/packages/ch.deletescape.lawnchair.plah/) ou [KISS Launcher](https://f-droid.org/en/packages/fr.neamar.kiss/) (bem minimalista)

## Produtividade

|Propósito|App proprietário|App código aberto|
|-------|---------------|--------|
|Armazenamento na nuvem|[Google Drive](https://play.google.com/store/apps/details?id=com.google.android.apps.docs), [OneDrive](https://play.google.com/store/apps/details?id=com.microsoft.skydrive), [Dropbox](https://play.google.com/store/apps/details?id=com.dropbox.android)|[Nextcloud](https://nextcloud.com/) (auto-host)|
|Email|[Gmail](https://play.google.com/store/apps/details?id=com.google.android.gm), app padrão de Email do seu celular|[K-9 Mail](https://f-droid.org/en/packages/com.fsck.k9/), [pEp](https://f-droid.org/packages/security.pEp/)|
|Sincronizador de calendário|[Calendário do Google](https://www.google.com/calendar/about/)|[Calendário Nextcloud](https://apps.nextcloud.com/apps/calendar)|
|Cliente de Calendário|[Calendário do Google](https://play.google.com/store/apps/details?id=com.google.android.calendar)|[Simple Calendar](https://f-droid.org/packages/com.simplemobiletools.calendar/)|
|Tarefas|[Wunderlist](https://play.google.com/store/apps/details?id=com.wunderkinder.wunderlistandroid), [Google Tasks](https://play.google.com/store/apps/details?id=com.google.android.apps.tasks)|[Tasks](https://f-droid.org/en/packages/org.dmfs.tasks/) (Sincroniza com Nextcloud Tasks com DAVdroid)|
|Leitor de PDF|[Google PDF Viewer](https://play.google.com/store/apps/details?id=com.google.android.apps.pdfviewer&hl=en_US)|[Document Viewer](https://f-droid.org/en/packages/org.sufficientlysecure.viewer/), [MuPDF](https://f-droid.org/en/packages/com.artifex.mupdf.viewer.app/)|

## Mensagens Instantâneas

Nota: Várias redes de mensageiros instantâneos não tem um cliente código aberto ou mesmo uma API para criá-lo. 😥

* [Telegram](https://f-droid.org/en/packages/org.telegram.messenger/) - Plataforma de mensagens, similar ao WhatsApp (fork FOSS, não use a versão da Google Play pois possui dependências proprietárias!)
* [Conversations](https://f-droid.org/en/packages/eu.siacs.conversations/) - Suporte a padrões atualizados, modernos e mantidos com XMPP client para Android
* [Signal](https://signal.org/android/apk/) ([Código aberto](https://github.com/signalapp/Signal-Android), APK proprietário, possui dependências Google!)
* [Riot.im](https://f-droid.org/packages/im.vector.alpha/) - Cliente Matrix
* Facebook Messenger - [MaterialFBook](https://github.com/ZeeRooo/MaterialFBook) com suporte a mensagens!

## Mídia Social

|App proprietário|App FOSS/Cliente Baseado na Web como alternativa|
|---------------|-------------------------------------|
|Reddit|[Slide](https://f-droid.org/en/packages/me.ccrama.redditslide/)|
|[Twitter](https://play.google.com/store/apps/details?id=com.twitter.android)|Use o site móvel [Twitter Lite](https://mobile.twitter.com/home) e adicione na sua home screen|
|[Facebook](https://play.google.com/store/apps/details?id=com.facebook.katana&hl=en)|[MaterialFBook](https://github.com/ZeeRooo/MaterialFBook) (Site móvel aprimorado para Facebook)|
|[Instagram](https://play.google.com/store/apps/details?id=com.instagram.android)|Use o site móvel [Instagram mobile site](https://www.instagram.com/) e adicione na sua home screen ([mais informações aqui](https://www.androidpolice.com/2017/05/10/instagram-new-mobile-web-app-ability-upload-photos/))|

## Outros

|App proprietário|App código aberto|
|---------------|--------|
|[YouTube](https://play.google.com/store/apps/details?id=com.google.android.youtube&hl=en)|[NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/) (Cliente Youtube), [YouTube Vanced](https://forum.xda-developers.com/android/apps-games/app-youtube-vanced-edition-t3758757) (Proprietário, versão modificada do app original sem propagandas, etc.)
|Google Assistant|[Just Search](https://f-droid.org/packages/co.pxhouse.sas/) (apenas pesquisa, mas funciona para o botão (pressionamento do botão home)) ou Fennec F-Droid/Firefox's Assist Feature (abre uma caixa URL no app)|

<!--

## Basics

|Purpose|Proprietary app|FOSS App|
|-------|---------------|--------|

-->

## Provedores de DNS

É importante escolher a privacidade respeitando o provedor de DNS.

Alguns que recomendo podem ser encontrados na [minha wiki](https://wiki.lelux.fi/dns/resolvers).

Use o [DNS-over-TLS](https://wiki.lelux.fi/dns-over-tls/#android), DNS-over-HTTPS ou DNSCrypt se possível para criptografar sua conexão.

Você pode mudar o provedor DNS por exemplo em [Blokada](https://blokada.org/) ou [Nebulo](https://smokescreen.app/) (DNS-over-TLS & DNS-over-HTTPS).


## Alguns outros apps e links úteis

* [Minhas recomendações para Firefox](https://github.com/theel0ja/firefox-recommendations/blob/master/README.md) (Original)
* [Recomendações para uBlock Origin](https://github.com/theel0ja/ubo-recommendations/blob/master/README.md)
* [Telegram-FOSS Offtopics](https://t.me/tfossofftop) (general discussion about Free and Open Source software)
* [Pequeno guia para privacidade e segurança no Android](https://t.me/AOSDPx/80) por [@Thespartann](https://github.com/Thespartann)
* [Grupo de suporte ao Micro G no Telegram](https://t.me/microGSupport) 
 

- ![#03363D](https://github.com/Griggorii/chromium-browser_setting_linux_3.0_chrome_chromium_flags_Command-Line) `#03363D`
# chromium-browser_setting_linux_3.0_chrome_chromium_flags_Command-Line
flags , griggorii , patent , find , example , registration , chrome , chromium , ffmpeg

New version google-chrome-unstable_88.0.4292.2-1 https://www.ubuntuupdates.org/pm/google-chrome-stable

Chrome , chromium v88 wayland 100% example google-chrome-unstable /usr/share/applications/google-chrome-unstable.desktop replace my version restart session run wayland setting browser.

root browser run setting no sandbox

________________________________________________________________________________________________________

+chromium default profile local state

Local State copy to replace in folder ~/.config/chromium

Local State example copy to opera , google-chrome , Brave-Browser

and opera ~/.config/opera

and google-chrome ~/.config/google-chrome

and google-chrome ~/.config/google-chrome-unstable

and brave ~/.config/BraveSoftware/Brave-Browser

and alternative chromium platforme all browsers

Re run chromium , opera , chrome , brave and alternative chromium platforme all browsers

_______________________________________________________________________________________________________

Not ubuntu os not /usr/share/applications ? Variant chromium-browser.desktop

~/.local/share/applications re run session

Alternative run all flags cmd command not local state

________________________________________________________________________________________

/usr/lib/chromium-browser/chromium-browser --cross-origin-isolated@1 --enable-ephemeral-guest-profiles-on-desktop@1 --enable-features=UseOzonePlatform --enable-future-v8-vm-features@1 --enable-generic-sensor-extra-classes@1 --enable-google-srp-isolated-prerender-nsp --enable-google-srp-isolated-prerender-probing@1 --enable-google-srp-isolated-prerenders@10 --enable-quic@1 --enable-webrtc-pipewire-capturer@1 --enable-zero-copy@1 --force-color-profile@1 --hardware-media-key-handling@1 --installed-apps-in-cbd@1 --load-media-router-component-extension@1 --omnibox-tab-switch-suggestions@1 --ozone-platform=wayland --pull-to-refresh@2 --tab-groups@1 --tab-hover-card-images@1 --use-sync-sandbox --flag-switches-begin --enable-accelerated-video-decode --enable-experimental-web-platform-features --isolated-prerender-nsp-enabled --enable-gpu-rasterization --enable-quic --enable-zero-copy --force-color-profile=srgb --ignore-gpu-blocklist --ignore-previews-blacklist --load-media-router-component-extension=1 --sync-url=https://chrome-sync.sandbox.google.com/chrome-sync/alpha --enable-features=UseOzonePlatform,ClickToCallUI,CrossOriginIsolated,GenericSensorExtraClasses,HardwareMediaKeyHandling,InstalledAppsInCbd,IsolatePrerenders,IsolatePrerendersMustProbeOrigin,OmniboxTabSwitchSuggestions,TabGroups,TabHoverCardImages,V8VmFuture,Vulkan --disable-features=EnableTLS13EarlyData,FontAccess,ScrollUnification --flag-switches-end

/usr/lib/chromium-browser/chromium-browser (windows example replace chromium.exe chrome.exe chromium-browser.exe brave.exe opera.exe yandex.exe) --copy my flags test

/(<source_browser>) --cross-origin-isolated@1 --enable-ephemeral-guest-profiles-on-desktop@1 --enable-features=UseOzonePlatform --enable-future-v8-vm-features@1 --enable-generic-sensor-extra-classes@1 --enable-google-srp-isolated-prerender-nsp --enable-google-srp-isolated-prerender-probing@1 --enable-google-srp-isolated-prerenders@10 --enable-quic@1 --enable-webrtc-pipewire-capturer@1 --enable-zero-copy@1 --force-color-profile@1 --hardware-media-key-handling@1 --installed-apps-in-cbd@1 --load-media-router-component-extension@1 --omnibox-tab-switch-suggestions@1 --ozone-platform=wayland --pull-to-refresh@2 --tab-groups@1 --tab-hover-card-images@1 --use-sync-sandbox --flag-switches-begin --enable-accelerated-video-decode --enable-experimental-web-platform-features --isolated-prerender-nsp-enabled --enable-gpu-rasterization --enable-quic --enable-zero-copy --force-color-profile=srgb --ignore-gpu-blocklist --ignore-previews-blacklist --load-media-router-component-extension=1 --sync-url=https://chrome-sync.sandbox.google.com/chrome-sync/alpha --enable-features=UseOzonePlatform,ClickToCallUI,CrossOriginIsolated,GenericSensorExtraClasses,HardwareMediaKeyHandling,InstalledAppsInCbd,IsolatePrerenders,IsolatePrerendersMustProbeOrigin,OmniboxTabSwitchSuggestions,TabGroups,TabHoverCardImages,V8VmFuture,Vulkan --disable-features=EnableTLS13EarlyData,FontAccess,ScrollUnification --flag-switches-end

chrome://ukm/

chrome://inspect/#devices Open dedicated DevTools for Node

griggorii@gmail.com нужно оборудование для разработки желательно конечно супер компьютер , но можно обойтись просто мощным железом желательно 16-32 разрядным процессором , на данный момент инвестиции в мою разработку нет , на уровне государства сидят те кто в основе делает вид что помогает. Мог бы перебрать хром если бы было все мощное и высоко скоростное с этими флагами , но нету оборудования так как надо его покупать , а это не в игрушки играть в ядре и тратить бюджет и многие кто собирает это понимает в ит сектор в россии подложена свинья в виде привилегированных отделов по этому даже мой дистрибутив не то что бы не поддержан инвестициями , но и не поддержан узнаваемостью что бы пользовались и все работало и дало как обход монетизации вне бюджета мог бы получить с той же платформы ютуба в которой указывался кошелек для обратной связи , но если кто заинтересован в альтернативном ядре и дистрибутиве то он тут https://youtu.be/9B-nTJyEZX0 естественно настройки подбираются что бы позднее дистрибутив работал ещё лучше , даже в данном случае настройки браузера в chrome://gpu/ могли бы уже быть пересобраны в хромиум по дефолту и навряд ли эти флаги не заработали на каких либо устройствах , пока дела плохи одни захватили станок , а другие инвестиции на деятельность и при том они уже как два года не могут выпустить полностью ускоренный браузер свои наработки я не беру с потолка за основу было взято исследование феномена первью от ютуба https://youtu.be/RrmsmJXYfTM позднее все настройки долго подобирались мной к этому результату что  https://youtu.be/I2aHs2mRtXc по сколько хромиум ос выдавал такое первью и был полностью ингуглед то навряд ли в медиа ключе была какая то уязвимость может только в авто воспроизведении ну так я могу и баш поставить на плей командой типа (make_eof_./my_bash.sh)<- вот и все воспроизведение не точно так же прибить можно будет такой скрипт два раза выполнив ctrl+c , а примерно , хотя в условиях современного веба об уязвимостях лучше вообще не рассуждать одна большая. Благо моими флагами можно сразу посмотреть результат работы не собирая как прототип пока я прибираюсь в настройках. На данный момент tls 1.3 для эксперимента отключен и все работает , но имеются проблемы с прокрукой колесом мыши все становиться очень медленным данный вопрос будет решен как будет найден тот флаг что мешает , а может это что то надо править в сорсах кода.

_______________________________________________________________________________________________________________________________________________________________

Version variant color auto change tab group , close browser close fone background

(Auto_color_tab_group_flag_by_griggorii_Local State.txt) rename to (Local State) and chrome://flags/ tab-groups-collapse enabled

Local State copy to replace in folder ~/.config/chromium example https://www.youtube.com/watch?v=I2aHs2mRtXc

Re run chromium

_______________________________________________________________________________________________________________________________________________________________

Optional chrome://flags/ find decode enable Hardware-accelerated video decode , YUV decoding for JPEG , YUV Decoding for WebP , H.264 Decoder Buffer Is Complete Frame , Enable AVIF image forma

Original technology auto color change griggorii@gmail.com

Пишите wayland легче иксов и на сколько вы это видите и помните настоящие первые открытые технологии тут и еще где то где сидят более честные люди, априори не может быть у остальных идет срисовывание и копирование моих настроек и распил гос бюджета иначе бы они мне переслали денег или финансировали это какими либо другими вещами , думаю когда выйдут новые виндовс и другие новые окружения и дистрибутивы линукс в них уже будет wayland или же остается надеется что бы не идти по грабля по скольку уже видно на сколько окна wayland легки и быстры в отличии от X11 так еще и compiz в комплекте что свидетельствует о растягивании окна операционной системы как пластелин обхватывая монитор любого размера без установки видео драйверов , а теперь уже просто прокладок под систему. Теперь думаю все понимают почему допустим microsoft хочет купить chromium для своего edge что бы тем самым забрать патент на wayland , но wayland еще и требует драйвер от mesa для легкости работы и в основе моего видео драйвера лежит скорость , блягодаря некому багу моего (модифицированного из за этого и баг) компилятора видео драйвер удалось сделать очень маленького размера подобно тому что делает комманда strip при сборке удаляя жирную кучу не нужнойстей или (make -d , но это немного другое там удаляются символьные ссылки если их так обозвать , можно использовать с командой -i что еще и пропустит некоторые библиотеки которые уйдут в ошибки если не смогут собраться , но это не значит что работоспособность обязательно измениться опять же установить всё это можно будет подобной командой sudo make install -i можно выставить скорость на каждое ядро если компьютер допустим 2-ядерный и вы не собираете какой то сверх тяжелый тулчеин , компилятор , браузер итд который требует минимум 18-50 Гигабайт свопа и вы пошли пить кофе и.т.д и более ничего не делаете на компьюторе то можно поставить еще и флаг make -j2 -i ) сам драйвер тут https://github.com/Griggorii/mesa-20.1.5_v2_ubuntu-19.04-20.04-20.10_X86_64_graphics

Не понятно пока по настройкам типа https://chrome-sync.sandbox.google.com/chrome-sync/alpha вот их полный вид ниже:

about_sync_data

{"actionable_error":[{"is_valid":false,"stat_name":"Error Type","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Action","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"URL","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Error Description","stat_value":"Uninitialized"}],"actionable_error_detected":false,"details":[{"data":[{"is_valid":true,"stat_name":"Transport State","stat_value":"Disabled"},{"is_valid":true,"stat_name":"Disable Reasons","stat_value":"Not signed in"},{"is_valid":true,"stat_name":"Sync Feature Enabled","stat_value":false},{"is_valid":true,"stat_name":"Setup In Progress","stat_value":false},{"is_valid":true,"stat_name":"Auth Error","stat_value":"OK since browser startup"}],"is_sensitive":false,"title":"Summary"},{"data":[{"is_valid":true,"stat_name":"Client Version","stat_value":"Chromium Linux 88.0.4282.0 (b2a7b0cc4ec6752e1ada55112ceefa2097f3d364-refs/heads/master@{#813514}) unknown"},{"is_valid":true,"stat_name":"Server URL","stat_value":"https://chrome-sync.sandbox.google.com/chrome-sync/alpha"}],"is_sensitive":false,"title":"Version Info"},{"data":[{"is_valid":true,"stat_name":"Requested Token","stat_value":"n/a"},{"is_valid":true,"stat_name":"Received Token Response","stat_value":"n/a"},{"is_valid":true,"stat_name":"Last Token Request Result","stat_value":"OK"},{"is_valid":true,"stat_name":"Has Token","stat_value":false},{"is_valid":true,"stat_name":"Next Token Request","stat_value":"not scheduled"}],"is_sensitive":false,"title":"Credentials"},{"data":[{"is_valid":true,"stat_name":"Server Connection","stat_value":"not attempted"},{"is_valid":true,"stat_name":"Last Synced","stat_value":"Never"},{"is_valid":true,"stat_name":"Sync First-Time Setup Complete","stat_value":false},{"is_valid":false,"stat_name":"Sync Cycle Ongoing","stat_value":false},{"is_valid":true,"stat_name":"Local Sync Backend Enabled","stat_value":false},{"is_valid":false,"stat_name":"Local Backend Path","stat_value":"Uninitialized"}],"is_sensitive":false,"title":"Local State"},{"data":[{"is_valid":false,"stat_name":"Throttled or Backoff","stat_value":false},{"is_valid":false,"stat_name":"Retry Time","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Notifications Enabled","stat_value":false}],"is_sensitive":false,"title":"Network"},{"data":[{"is_valid":false,"stat_name":"Explicit Passphrase","stat_value":false},{"is_valid":false,"stat_name":"Passphrase Required","stat_value":false},{"is_valid":false,"stat_name":"Cryptographer Ready To Encrypt","stat_value":false},{"is_valid":false,"stat_name":"Cryptographer Has Pending Keys","stat_value":false},{"is_valid":false,"stat_name":"Encrypted Types","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Has Keystore Key","stat_value":false},{"is_valid":false,"stat_name":"Keystore Migration Time","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Passphrase Type","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Passphrase Time","stat_value":"Uninitialized"}],"is_sensitive":false,"title":"Encryption"},{"data":[{"is_valid":false,"stat_name":"Sync Source","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"GetKey Step Result","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Download Step Result","stat_value":"Uninitialized"},{"is_valid":false,"stat_name":"Commit Step Result","stat_value":"Uninitialized"}],"is_sensitive":false,"title":"Status from Last Completed Session"},{"data":[{"is_valid":false,"stat_name":"Notifications Received","stat_value":0},{"is_valid":false,"stat_name":"Updates Downloaded","stat_value":0},{"is_valid":false,"stat_name":"Tombstone Updates","stat_value":0},{"is_valid":false,"stat_name":"Reflected Updates","stat_value":0},{"is_valid":false,"stat_name":"Successful Commits","stat_value":0},{"is_valid":false,"stat_name":"Conflicts Resolved: Client Wins","stat_value":0},{"is_valid":false,"stat_name":"Conflicts Resolved: Server Wins","stat_value":0}],"is_sensitive":false,"title":"Running Totals"},{"data":[{"is_valid":false,"stat_name":"Encryption Conflicts","stat_value":0},{"is_valid":false,"stat_name":"Hierarchy Conflicts","stat_value":0},{"is_valid":false,"stat_name":"Server Conflicts","stat_value":0},{"is_valid":false,"stat_name":"Committed Items","stat_value":0}],"is_sensitive":false,"title":"Transient Counters (this cycle)"},{"data":[{"is_valid":false,"stat_name":"Updates Downloaded","stat_value":0},{"is_valid":false,"stat_name":"Committed Count","stat_value":0},{"is_valid":false,"stat_name":"Entries","stat_value":0}],"is_sensitive":false,"title":"Transient Counters (last cycle of last completed session)"}],"type_status":[],"unrecoverable_error_detected":false}

#03363D #03363D

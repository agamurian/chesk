# chesk
chesk is web-based general purpose 3D editor, aim to be simple, concise and convinient.


Chesk is 3d editor, not like others, it works in your browser.

Because of amazing tech of the last decade 3D and graphics on webpages changed tremendously. Now JS programs (Basicly, websites) can run WEBGL canvas on a client`s browser using the GPU of the client.
That changed the picture. 3D in your browser can actually be fast and suitable for games, editors, and everything else. Depends on your hardware. And this tech works on almost ANY device.

With svelte reactivity, Threejs great api and amazing Threlte package this editor should be fast anogth for basic 3d work.
-------

It have 2 mods of viewing the file based on rights of the user:
 - View mode (some configurations allowed)
 - Project mode (editing the project)

-------

### Basic values are **Projects**:
  they are avalible to different users via shares, and stored on the server.
  every project is represented with folder on server with other folders and files.
  settings of the project are stored on **project.yaml** file.

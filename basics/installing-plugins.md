# Installing plugins

You can download various plugins here:

{% content-ref url="https://app.gitbook.com/o/-MhmG2mhIIHTtQPuHV_k/s/klCVENFte0GRy5IqVz0W/" %}
[Audacity Plugins](https://app.gitbook.com/o/-MhmG2mhIIHTtQPuHV\_k/s/klCVENFte0GRy5IqVz0W/)
{% endcontent-ref %}

Most plugins get automatically activated once you install them on your system.

{% hint style="warning" %}
**Caution:**

* 64-bit Audacity cannot run 32-bit plugins, and 32-bit Audacity cannot run 64-bit plugins. Make sure they match.
* "Instrument" versions of plugins (VSTi, LV2i) are not supported.
{% endhint %}

## Manually installing plugins

{% tabs %}
{% tab title="Windows" %}
* VST2:  `C:\Program Files\Common Files\VST2` or `C:\Program Files\Steinberg\VSTPlugins`
* VST3: `C:\Program Files\Common Files\VST3` or `C:\Program Files\Steinberg\VSTPlugins`
* LV2:  `C:\Program Files\Common Files\LV2`\
  **Note:** Always copy the complete .lv2 _folder_
* LADSPA: `C:\Users\<username>\Appdata\Roaming\audacity\Plug-ins\`
* Vamp: `C:\Program Files\Vamp Plugins\`
* Nyquist: See below
{% endtab %}

{% tab title="macOS" %}
All Plugins can be installed per-user (`~/Library/Audio/Plug-Ins/...`) or system-wide (`/Library/Audio/Plug-Ins/...`). In following, only the system-wide path is named

* Audio Unit: `/Library/Audio/Plug-Ins/Components/`
* VST2 and VST3: `/Library/Audio/Plug-Ins/VST/`
* LV2: `~/.lv2` or `/Library/Audio/Plug-Ins/LV2`,\
  **Note:** always copy the entire .lv2 _folder_
* Vamp: `/Library/Audio/Plug-Ins/Vamp`
* Nyquist: See below
{% endtab %}

{% tab title="Linux" %}
* LV2: `~/.lv2`, `/usr/local/lib/lv2` (for 32-bit) or `/usr/local/lib64/lv2` (for 64-bit)\
  **Note**: Always copy the entire .lv2 _folder_
* VST2 and VST3: `~/.vst` or `/usr/local/lib/vst`\
  \`\`**Note**: Many VST effects are Windows-only
* LADSPA: `~/.ladspa` or `/usr/local/lib/ladspa`
* Vamp: `~/.vamp` or `/usr/local/lib/vamp`
* Nyquist: See below
{% endtab %}
{% endtabs %}

## Installing Nyquist plugins

{% embed url="https://youtu.be/BMZ5gwkn2uo" %}
Watch a step-by-step tutorial of this guide
{% endembed %}

To install a Nyquist Plugin, follow these steps:

1. Download the plugin in question.
2. Open Audacity, and go to **Tools > Nyquist Plugin Installer**
3. Click **Browse** and locate your downloaded plugin
4. Click **Open** and then **OK** and **OK** again.
5. Go to **Effect > Add/Remove Plugins**
6. Scroll to the plugin you just installed
7. Enable the plugin by selecting it and clicking **Enable**
8. Click **OK**

## Deactivating and re-activating plugins

1. Go to **Tools -> Plugin-Manager**
2. Select the plugins or effects you want to deactivate
3. Click **Disable**.
4. To re-enable a plugin, select them and click **Enable**.

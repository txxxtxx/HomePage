# 激活相关

#### Windows系统激活

{% tabs %}
{% tab title="方法一" %}
```
slmgr -skms kms.03k.org
slmgr -ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
slmgr -ato
```
{% endtab %}

{% tab title="方法二" %}
```
irm https://massgrave.dev/get | iex
```
{% endtab %}
{% endtabs %}

#### Office系统激活

```
C:\Program Files\Microsoft Office\Office16
cscript ospp.vbs /sethst:kms.03k.org
cscript ospp.vbs /act
```

#### IDM激活

```
iex(irm is.gd/idm_reset)
或者
iwr -useb https://raw.githubusercontent.com/lstprjct/IDM-Activation-Script/main/IAS.ps1 | iex
```

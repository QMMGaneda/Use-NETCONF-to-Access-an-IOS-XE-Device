# Use-NETCONF-to-Access-an-IOS-XE-Device

CSR1kv# show platform software yang-management process 

CSR1kv# config t

CSR1kv (config)# netconf-yang

devasc@labvm:~$ ssh cisco@192.168.56.101 -p 830 -s netconf

cisco@192.168.56.101's password:


<hello xmlns="urn:ietf:params:xml:ns:netconf:base:1.0">
 <capabilities>
   <capability>urn:ietf:params:netconf:base:1.0</capability>
 </capabilities>
</hello>
]]>]]>


CSR1kv> en
CSRk1v# show netconf-yang sessions

<rpc message-id="103" xmlns="urn:ietf:params:xml:ns:netconf:base:1.0">
 <get>
  <filter>
    <interfaces xmlns="urn:ietf:params:xml:ns:yang:ietf-interfaces"/>
   </filter>
 </get>
</rpc>
]]>]]>


<rpc message-id="9999999" xmlns="urn:ietf:params:xml:ns:netconf:base:1.0">
 <close-session />
</rpc>

CSR1kv# show netconf-yang sessions

pip3 list --format=columns

pip3 install ncclient

pip3 list --format=columns | more














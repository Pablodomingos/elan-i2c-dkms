## Touch - Lenovo na distro Pop_Os!

### Instale o Grub https://www.youtube.com/watch?v=wLOZfT0732Y

### Atualize o kernel
#### 1º Rode o comando -> sudo <editor de sua preferencia/> /etc/default/grub
#### 2º Em GRUB_CMDLINE_LINUX_DEFAULT adicione "i8042.nopnp=1 pci=nocrs"
#### 3º Salve o arquivo
#### 4º Rode o comano sudo update-grub
#### 5º Reinicie o sistema

## Sé ainda não funcionou

### Faça o fork do https://github.com/Pablodomingos/elan_i2c_dkms
#### cd touch_lenovo_dkms
#### sudo dkms install .
#### Reinicie o sistema

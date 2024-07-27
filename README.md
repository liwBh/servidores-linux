# Apache

- Iniciar Apache manualmente
```
sudo systemctl start apache2
```

- Detener Apache
```
sudo systemctl stop apache2
```

- Reiniciar Apache
```
sudo systemctl restart apache2
```

- Habilitar Apache para que se inicie automáticamente al arrancar
```
sudo systemctl enable apache2
```

- Deshabilitar Apache para que no se inicie automáticamente al arrancar
```
sudo systemctl disable apache2
```

# PostgreSQL

- Iniciar PostgreSQL manualmente
```
sudo systemctl start postgresql
```

- Detener PostgreSQL
```
sudo systemctl stop postgresql
```

- Reiniciar PostgreSQL
```
sudo systemctl restart postgresql
```

- Habilitar PostgreSQL para que se inicie automáticamente al arrancar
```
sudo systemctl enable postgresql
```

- Deshabilitar PostgreSQL para que no se inicie automáticamente al arrancar
```
sudo systemctl disable postgresql
```

# MySQL

- Iniciar MySQL manualmente
```
sudo systemctl start mysql
```

- Detener MySQL
```
sudo systemctl stop mysql
```

- Reiniciar MySQL
```
sudo systemctl restart mysql
```

- Habilitar MySQL para que se inicie automáticamente al arrancar
```
sudo systemctl enable mysql
```

- Deshabilitar MySQL para que no se inicie automáticamente al arrancar
```
sudo systemctl disable mysql
```

# NetworkManager

- Reiniciar el servicio de red
```
sudo systemctl restart NetworkManager
```

- Cambiar a servidor DNS  público
```
sudo nano /etc/resolv.conf
```
- Modificar el nameserver
```
nameserver 8.8.8.8
```




# Respaldo de Alias de Zsh

Este repositorio contiene mis alias en el archivo `.aliases`.

---

## 🔹 Cómo actualizar el respaldo

1. Editar ~/.aliases en tu home.

2. Copiar y pegar manualmente esos cambios aquí:
   vim ~/mis-alias/.aliases


3. Guardar en Git:
   cd ~/mis-alias
   git add .aliases
   git commit -m "feat: actualizo alias de zsh"
   git push



## 🔹 Cómo usar en un computador nuevo

1. Clonar el repositorio:
   git clone git@github.com:vflorest/mis-alias.git ~/mis-alias

2.Copiar el archivo a tu home:   
   cp ~/mis-alias/.aliases ~/

3.Editar ~/.zshrc y agregar (si no existe):
   [ -f ~/.aliases ] && source ~/.aliases

3. Recargar la configuración:
   source ~/.zshrc


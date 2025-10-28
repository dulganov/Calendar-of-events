Для запуска необходимо разархировать два файла, и один из них src заменить или вложить в папку quasar-front

python -m venv .venv

.venv\Scripts\activate

добавить папки из архива рядом с пространством venv

cd backend

pip install -r requirements.txt

cd quasar-front

npm install -g @quasar/cli

npm init quasar

quasar dev

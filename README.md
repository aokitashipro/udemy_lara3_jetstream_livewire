## Udemy講座 Laravel 第３弾 

Jetstream + Livewireまでインストールした環境です。<br /><br />

## インストール方法
git clone https://github.com/aokitashipro/udemy_lara3_jetstream_livewire.git uReserve
<br />
cd uReserve<br />
composer update<br />
cp .env.example .env<br />
.env のDB環境を編集する<br />
php artisan key:generate<br />
npm i && npm run dev<br />
php artisan migrate:fresh --seed<br />
php artisan serve
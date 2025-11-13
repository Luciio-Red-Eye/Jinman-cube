
.env.example
jinman-cube/
├─ README.md
├─ .env.example
├─ config/
│  ├─ cube.json
│  ├─ tradepoint.json
│  └─ agents.json
├─ scripts/
│  ├─ init_ipfs.sh
│  ├─ raise_jinman.sh
│  ├─ publish_state.sh
│  └─ emergency_flag.sh
├─ php/
│  ├─ .htaccess
│  ├─ config.php
│  ├─ endpoints/
│  │  ├─ status.php
│  │  ├─ raise.php
│  │  ├─ emergency.php
│  │  └─ subscribe.php
│  └─ lib/
│     ├─ signer.php
│     ├─ ipfs.php
│     └─ cube.php
├─ public/
│  ├─ index.html
│  └─ status.json
└─ deploy/
   ├─ ftp_push.sh
   └─ build.sh

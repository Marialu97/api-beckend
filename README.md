04.09.25
	CRIA UMA PASTA 
	api-beckend
	ABRE NO TERMINAL 

		TERMINAL
		node -v
		tem que esta na vercao v22.19

		[se não der escreve]
		[node download]
		[abaixa a vercao 22.19]
		npm -v
			VERCAO DO NPM
		npm install -g @nestjs/cli

		 nest new api-beckend
			se der errado
		npx nest new api-beckend
			vai pedir para escolher coloca (npm)
		cd ..
		npm rum start
			ESTARTAR O CERVIDOR 
		nest run start:dev
		
		ABRE NO VSCODE
		TERMINAL
		nest generate module products
		nest generate controller products
		nest generate service products --no-spec

		TEM QUE TER CRIADO NO 
		src
		products
		products.controller.ts
		products.module.ts
		products.service.ts

------------------------------------------------------------------
		ENTRA NAS PASTAS 
		products.controller.ts
		products.module.ts
		products.service.ts
		ESCREVE DENTRO

		ABAIXAMOS 
		https://www.postman.com/downloads/
              
		TERMINAL
		nest generate controller products
		nest generate service products --no-spec
 		npm install class-validator class-transformer 
		cd src
		cd .\products\
 		ls
		mkdir dto

		CRIA A PASTA 
		dto
		create-product.dto.ts 
 		update-product.dto.ts
		ESCREVE DENTRO 
		products.controller.ts
		ESCREVE O IMPORT
		main.ts
		ESCREVE DENTRO 

05.09.25
		MySQL 
		CRIA UM BANCO
		TERMINAL
		npm install @nestjs/typeorm typeorm mysql2

		ENTRA 
		app.module.ts
		ADICIONA UM IMPORT
		ESCREVE DENTRO 

		CRIA UMA PASTA 
		entities
		DENTRO DA PASTA 
		products
		
		DENTRO DA PASTA 
		entities
		FAZ A PASTA 
		products.entity.ts

		ESCREVE DENTRO
		app.module.ts
		products.service.ts
		products.controller.ts
		main.ts

		===================================
		MEU DEU POBLEMA CONTINUA DA QUI 
		==================================

		ENTRA NA PASTA DO PROJET 
		DA UM ABRIR NO TERMINAL 
 		npm create vite@latest frontend -- --template react-ts
		cd frontend
		npm install
		npm run dev
		npm install axios

		ABRE O VSCODE A PASTA FRONTIENDE QUE FOI CRIAD 
		NA PASTA 
		src
		CRIA A PASTA 
		services 
		DENTRO DA PASTA  
		services
		CRIAR O ARQUIVO 
		api.ts
		ESCREVE DENTRO 

		TERMINAL 
		ENTRA NA PASTA FRONTIENDE 
		VAI NO ABRIR TERMINAL E COLOCA
		npm run dev
		ENTRA NA PASTA API-BECKEND
		VAI NO ABRIR NO TERMINAL E COLOCA  
		npm run start:dev

		VAI NA PASTA E COLOCA NA PASTA 
		app.tsx
		ESCREVE DENTRO
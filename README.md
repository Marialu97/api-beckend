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
		
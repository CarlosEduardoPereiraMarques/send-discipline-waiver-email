<template>
    <div class="bg-white shadow rounded-md px-8 container mx-auto h-full flex justify-center items-center ">
        <div class="w-9/12 ">
        
            <h3 class="text-2xl font-semibold flex justify-center">Solicitação de dispensa de disciplina</h3>
            <div class="pt-5 grid grid-cols-2 sm:grid-cols-2 pb-2">
                <label for="student_name" class="mb-5">Nome: </label>
                    <input type="text" id="student_name" class="rounded bg-gray-100 border-2 border-gray-200 mb-5" placeholder="Nome do Aluno">
                <label for="coordinator_email" class="mb-5">Email: </label>
                    <input type="text" id="coordinator_email" class=" rounded bg-gray-100 border-2 border-gray-200 mb-5" placeholder="Email do Coordenador">
                <label for="email_body" class="mb-5">Corpo do email:</label>
                    <input type="text" id="email_body" class=" rounded bg-gray-100 border-2 border-gray-200 mb-5" placeholder="Digite aqui seu email">
                <label for="attachment" class="mb-5">Anexo: </label>
                    <input type="file" id="attachment" class="rounded bg-gray-100 border-2 border-gray-200 mb-5" placeholder="Insira o Anexo">
            </div>
            <div class="flex justify-center mb-5">
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"> 
                    Enviar Email 
                </button>
            </div>
        </div>

    </div>
</template>

<script setup>

</script>

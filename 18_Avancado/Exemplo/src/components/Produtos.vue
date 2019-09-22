<template>
    <div class="container">
        <table class="table table-striped mt-4">
            <thead>
                <tr>
                    <th scope="col">#</th>
                    <th scope="col">ID</th>
                    <th scope="col">Titulo</th>
                </tr>
            </thead>
            <tbody>
                <tr v-for="produto in produtos" :key="produto.id">
                    <th scope="row">1</th>
                    <td>{{produto.id}}</td>
                    <td>{{produto.titulo}}</td>
                </tr>
            </tbody>
        </table>
    </div>
</template>

<script>
export default{
    name: 'ProdutosExemplo',
    data(){
        return{
            produtos:[
                {id:1, titulo:'Produto 1'},
                {id:2, titulo:'Produto 2'},
                {id:3, titulo:'Produto 3'},
                {id:4, titulo:'Produto 4'}
            ]
        }
    }
}
</script>

<style>

</style>

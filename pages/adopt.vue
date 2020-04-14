<template>
   <div class="bg-blue-400 h-screen w-screen">
    <div class="flex flex-col items-center flex-1 h-full justify-center px-4 sm:px-0">
        <div class="flex rounded-lg shadow-lg w-full sm:w-3/4 lg:w-1/2 bg-white sm:mx-0" style="height: 500px">
            <div class="flex flex-col w-full md:w-1/2 p-4">
                <div class="flex flex-col flex-1 justify-center mb-8">
                    <h1 class="text-4xl text-center font-thin">Adopt</h1>
                    <div class="w-full mt-4">
                        <form class="form-horizontal w-3/4 mx-auto">
                            <div class="flex flex-col mt-4">
                                <input  type="text" class="flex-grow h-8 px-2 border rounded border-grey-400" placeholder="Dog">
                            </div>
                            <div class="flex flex-col mt-4">
                                <input type="text" class="flex-grow h-8 px-2 border rounded border-grey-400" placeholder="Race">
                            </div>
                            <div class="flex flex-col mt-4">
                                <input type="text" class="flex-grow h-8 px-2 border rounded border-grey-400" placeholder="Size">
                            </div>
                              <div class="flex flex-col mt-4">
                               <select class="flex-grow border rounded border-grey-400 px-2 h-8">
                                   <option>Famale</option>
                                   <option>Male</option>
                               </select>
                            </div>
                            
                            <div class="flex flex-col mt-8">
                                <button type="submit" class="bg-blue-500 hover:bg-blue-700 text-white text-sm font-semibold py-2 px-4 rounded">
                                    Adopt
                                </button>
                            </div>
                        </form>
                        
                        
                    </div>
                </div>
            </div>
            <div class="hidden md:block md:w-1/2 rounded-r-lg" style="background: url('https://images.unsplash.com/photo-1559190394-df5a28aab5c5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60'); background-size: cover; background-position: center center;"></div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>
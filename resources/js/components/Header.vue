<template>
    <div class="font_bold  text-3xl uppercase  mx-auto max-w-screen-xl px-4 sm:px-6 lg:px-8">

        <div class="ml-6 mt-6 mb-2">
            <div class="sm:hidden  ">
                <label for="Tab" class="sr-only">Tab</label>

                <select id="Tab" class="w-full rounded-md border-green-600">
                    <option>

                        <img src="./logo.png" alt="Мое изображение">
                    </option>
                    <option>Новости</option>
                    <option>Популярные разделы</option>
                    <option>Предложения</option>
                    <option>Контакты</option>
                </select>
            </div>

            <div class="hidden sm:block">
                <div class="">
                    <nav class="-mb-px flex gap-6" aria-label="Tabs">
                        <a
                                href="#"
                                class="shrink-0 border-b-2 border-transparent px-1 pb-4 text-sm font-medium text-green-700 hover:border-green-600 hover:text-green-800"
                        >
                            Новости
                        </a>
                        <a
                                href="#"
                                class="shrink-0 border-b-2 border-transparent px-1 pb-4 text-sm font-medium text-green-700 hover:border-green-600 hover:text-green-800"
                        >
                            Популярные разделы
                        </a>
                        <a
                                href="#"
                                class="shrink-0 border-b-2 border-transparent px-1 pb-4 text-sm font-medium text-green-700 hover:border-green-600 hover:text-green-800"
                        >
                            Предложения
                        </a>
                        <a
                                href="#"
                                class="shrink-0 border-b-2 border-transparent px-1 pb-4 text-sm font-medium text-green-700 hover:border-green-600 hover:text-green-800"
                                aria-current="page"
                        >
                            Контакты
                        </a>
                        <a
                                href="#"
                                class="shrink-0 ml-[25rem] border-b-2 border-transparent px-1 pb-4 text-sm font-medium text-green-700 hover:border-green-600 hover:text-green-800"
                                aria-current="page"
                        >
                            Персональная страница
                        </a>
                    </nav>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>

</style>
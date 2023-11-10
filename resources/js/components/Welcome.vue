<template>
    <section class="w-full py-32 relative"
             style="background-image: url('https://images.pexels.com/photos/122429/leaf-nature-green-spring-122429.jpeg');">
        <div class="absolute inset-0" style="background-color: rgba(0, 0, 0, 0.5);"></div>
        <div class="container h-[20rem] mx-auto text-center text-block">
            <h1 class="text-5xl font-medium mb-6 text-white">Добро пожаловать в агенство LocalMedia</h1>
            <p class="text-xl mb-12">
                Опыт совершенства в рекламе: добро пожаловать в наш мир LocalMedia, где
                творчество сочетается со стратегией. Мы динамичное рекламное агентство, специализирующееся на
                создании убедительных
                кампании, которые захватывают аудиторию. Наша команда сочетает инновации с опытом, чтобы обеспечить
                индивидуальный подход
                решения для вашего бренда. Исследуйте силу эффективного сторителлинга и целевого маркетинга
                стратегии с LocalMedia. Позвольте нам усилить голос вашего бренда в цифровой среде и
                вне.</p>


            <div class="flex justify-center">


                <div class="w-[38rem] flex">

                    <div>
                        <label for="UserEmail" class=" text-2xl font-medium leading-6 text-white">
                            Найти компанию
                        </label>
                        <select
                                name="HeadlineAct"
                                id="HeadlineAct"
                                class="text-gray-900  mt-2 h-[2rem] w-full rounded-md border-gray-200 shadow-sm sm:text-sm"

                        >
                            <option value="">Минск</option>
                            <option value="JM">Минская область</option>
                            <option value="JM">Минская область</option>
                            <option value="JM">Минская область</option>

                        </select>
                    </div>

                    <div class="ml-2">
                        <label for="UserEmail" class=" text-2xl font-medium leading-6 text-white">
                            Название компании
                        </label>

                        <input
                                type="email"
                                id="UserEmail"
                                placeholder="Введите название"
                                class="mt-2 pl-2 h-[2rem] w-full rounded-md border-gray-200 shadow-sm sm:text-sm"
                        />
                    </div>


                </div>


                <div class="w-[18rem] ml-28">
                    <label for="UserEmail" class="block text-2xl font-medium leading-6 text-white">
                        Добавить компанию
                    </label>

                    <input
                            type="email"
                            id="UserEmail"
                            placeholder="Введите название"
                            class="mt-3 pl-2 h-[2rem] w-full rounded-md border-gray-200 shadow-sm sm:text-sm"
                    />
                </div>
            </div>

        </div>
    </section>
</template>

<script>
export default {
    name: "Welcome"
}
</script>

<style scoped>

</style>
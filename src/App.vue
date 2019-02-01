<template lang="pug">
  .font-sans.antialiased.h-screen.flex.flex-col(id="app")
    Bar.flex-shrink/
    .flex-1.bg-grey-lighter.max-h-full
      //-
      .flex.bg-grey-lighter.max-h-full
        .flex-1.text-grey-darker.text-center.bg-grey-light.m-2.px-2.py-2
          .flex.flex-col.bg-grey-lighter.h-full
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.m-2(class="h-1/3")
              .flex.flex-col.content-center
                .text-grey-darker.bg-grey-light.px-4.py-2
                  label.text-center Source station
                .text-grey-darker.bg-grey-light.px-4.py-2.pr-8
                  select.pl-2.w-full.bg-white.border.border-grey-light.shadow.leading-tight.h-8(class="focus:outline-none")
                    option Station 1
                    option Station 2


            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.m-2(class="h-1/3")
              .flex.flex-col.bg-grey-lighter.content-center
                .text-grey-darker.bg-grey-light.px-4.py-2
                  label.text-center Destination station
                .text-grey-darker.bg-grey-light.px-4.py-2.pr-8
                  select.pl-2.w-full.bg-white.border.border-grey-light.shadow.leading-tight.h-8(class="focus:outline-none")
                    option Station 1
                    option Station 2
                    option Station 3
                    option Station 4
                    option Station 5

            .text-grey-darker.text-center.px-2.py-2.m-2(class="h-1/3")
              .flex.flex-row
                button.bg-blue.text-white.font-bold.py-2.px-4.rounded.w-full(class="hover:bg-blue-dark") Calculate minimum path

        .flex-1.text-grey-darker.text-center.bg-grey-light.m-2
          .flex.flex-col.bg-grey-lighter.border-2.border-grey
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 1
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 2
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 3
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 4
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 5
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 6
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 7
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 8
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 9
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 10
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 11
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2.border-b-2.border-grey Station 12
            .text-grey-darker.text-center.bg-grey-light.px-2.py-2 Station 13
      router-view/
</template>

<script>
import Bar from '@/components/Bar'
export default {
  name: 'app',
  components: {
    Bar
  }
}
</script>

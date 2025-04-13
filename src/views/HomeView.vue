<script setup lang="ts">
import { Button } from '@/components/ui/button'
import { Card, CardHeader, CardTitle, CardContent, CardFooter } from '@/components/ui/card'
</script>

<template>
  <main class="flex flex-col items-center justify-center h-screen">
    <Card class="w-[50%]">
      <CardHeader>
        <CardTitle>Welcome to this template</CardTitle>
      </CardHeader>
      <CardContent class="">
        This is a template for a Vue 3 project with Tailwind 4 and shadcn vue components.
      </CardContent>
      <CardFooter class="flex justify-between">
        <Button>Footer</Button>
        <Button variant="outline">Outline</Button>
        <Button variant="ghost">Ghost</Button>
        <Button variant="link">Link</Button>
      </CardFooter>
    </Card>
  </main>
</template>

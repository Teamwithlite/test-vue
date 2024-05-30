<script setup lang="ts">
import TheWelcome from './components/TheWelcome.vue'
import Nav from './components/Nav.vue'
import {Button} from './components/ui/button'
import {Input} from './components/ui/input'
import {
  Card,
  CardContent,
  CardDescription,
  CardFooter,
  CardHeader,
  CardTitle,
} from './components/ui/card';
</script>

<template>
  <div>
    <div>
    <Nav msg="Vue.js Test"></Nav>
  </div>
  

  <div class="flex py-4 px-2">
    <Button>Submit</Button>
    <Input class="mx-2"></Input>
  </div>
    <div className="flex flex-col space-y-4 w-auto px-4 py-4">
        <div>
          <Card>
            <CardHeader>
              <CardTitle>Something</CardTitle>
              <CardDescription>I don't know</CardDescription>
            </CardHeader>
            <CardContent>
              <p>Content</p>
            </CardContent>
            <CardFooter>
              <p>Card Footer</p>
            </CardFooter>
          </Card>
        </div>
        <div>
          <Card>
            <CardHeader>
              <CardTitle>Card Title</CardTitle>
              <CardDescription>Card Description</CardDescription>
            </CardHeader>
            <CardContent>
              <p>Card Content</p>
            </CardContent>
            <CardFooter>
              <p>Card Footer</p>
            </CardFooter>
          </Card>
        </div>
      </div>
 </div>

</template>

<style scoped>
header {

}

.logo {
  display: block;

}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>

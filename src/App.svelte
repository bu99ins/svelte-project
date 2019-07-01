<script>
  import Header from "./UI/Header.svelte";

  const meetups = [
    {
      id: "m1",
      title: "Coding Bootcamp",
      subtitle: "Learn to code in 2 hours",
      description:
        "In this meetup we will have some experts that teach you how to code!",
      imageUrl:
        "https://patch.com/img/cdn20/users/22850531/20160831/112556/styles/raw/public/article_images/1196_kinky_boots_tour-1472656960-6789.jpg",
      address: "27th Nerd Road, 32523 New York",
      contactEmail: "code@test.com"
    },
    {
      id: "m2",
      title: "Swim Togethe",
      subtitle: "Let's go for some swimming",
      description: "We will simply swim some rounds!",
      imageUrl:
        "https://cdn.shopify.com/s/files/1/0400/5813/files/WebDBIMG_3974_2048x.jpg?v=1561446080",
      address: "27th Nerd Road, 32523 New York",
      contactEmail: "swim@test.com"
    }
  ];
</script>

<Header />

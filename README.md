# Agoracy

Sourced, even-handed explainers on public policy, written first as social media posts and later as a website.

The writing guide for every post is in [CLAUDE.md](CLAUDE.md).

## Layout

```
series/
  <series-name>/
    plan.md                 the series plan: topics, order, evidence, research gaps
    <NN>-<slug>/
      post.md               one post: front matter, post text, first comment (sources),
                            fact-check table, notes, editor's notes
      image.png             the post's image (1080x1080)
```

Each `post.md` starts with front matter (title, series, number, status, image, updated), so a static site generator such as Hugo, Jekyll or Astro can publish the same files later without restructuring.

## Series

- [Florida's voucher programs](series/florida-vouchers/plan.md): a 12-post series for legislators in other states. Post 1: [How Florida Went From Vouchers for a Few Children to Vouchers for Every Child](series/florida-vouchers/01-how-florida-got-here/post.md). Post 2 (draft): [Who Gets Florida's Vouchers, and Where Were They Before?](series/florida-vouchers/02-who-gets-vouchers/post.md). Post 3 (draft): [Charter Schools and Home Schooling](series/florida-vouchers/03-charters-and-home-schooling/post.md). Post 4 (draft): [Religious Schools and Florida's Vouchers](series/florida-vouchers/04-religious-schools/post.md). Post 5 (draft 5): [Do Florida's Vouchers Save Money?](series/florida-vouchers/05-what-vouchers-cost/post.md). Post 6 (draft 4): [Florida's Public Schools Now Lean on Rising Property Values](series/florida-vouchers/06-money-per-student/post.md).

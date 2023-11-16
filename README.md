# conquering_responsive_layouts

This repo focuses on dealing with responsive layouts with courses &amp; examples

# Day 1 ---

- Naturally without css all the websites are responsive, we make some changes to make the web non-responsive, hence we deal with responsiveness.

- ## Avoid giving heights
  > Instead give height: 100%,

# Day 2

> ## Code Pen & explanation videos links
>
> > code pen: [rem, em example](https://codepen.io/kevinpowell/pen/RKdjXe).
> > Reference : [em & rem explained](https://youtu.be/_-aDOAMmDHI?si=95p3mFROtT0u6-dq).
> > Reference : [Why you shouldn't set font-sizes using em](https://youtu.be/pautqDqa54I?si=BiSS70RjLNT_oskm).
>
> ## use em for : **paddings, margins**
>
> > Because these properties refer to their own font sizes, not their parent ones, so compounding will not affects here.
>
> ## use rem for : **font-sizes**
>
> > Becauses it refers to the root elememt html { font-size: 16px; }, it wont refer to the parent of parent, so compounding wont affect this.

# Day 3 | Enter max-width

> Giving fixed width is a bad idea,
> Instead we can use percentages, which make our lives easier.
> The only issue with this is, at large screens, things can get too big. Thankfully, we have max-width that can help us out!
>
> > Dont's
> > `width: 250px`
>
> > Do's
> >
> > ```
> > width: 80%;
> > max-width: 750px;
> > margin: 0 auto;
> > ```

```

```

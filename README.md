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

# Day 4 | Extra curricular activities

> CSS Units: vh, vw, vmin, vmax:
>
> > 0 to 1 minute: They are not only useful in layouts but also useful in responsive typographies.
> > 1 to 4 minute: using `height: 100vh` in a div, you might see on some websites as you login you can see.But this causes issues in > >>
> > mobile devices when coming to small screens, we need to fix it with media queries. we can also use `vw for width:`
> > 5 to 8 minute : Vmax : max(vw,vh), Vmin: min(vw,vh),
> > 8 to 9 minute : Giving `font-size: vw` font size of page title is good it changes according to vw, the problem with `vw` is for smaller screens it gets too small, for larger screens it gets too large. => solution we can handle with media-queries/clamp(). It best fits for screens sizes between `small < Best fit screen sizes < large`

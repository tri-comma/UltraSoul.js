# UltraSoul.js

UltraSoul.js is a lightweight library that extends the web UI.
It is implemented with the following policy.

- Does not depend on external libraries.
- Does not require css files.
- Does not change the structural tags.
- Extend the DOM with methods.

## References

### UI-Carousel: `HTMLCollection.ladyGoRound()`

Creates carousels that slides automatically without specifying css.

#### Example

```html
<div>
  <div class="lady-go-round" data-arg="15 7200 800 14">
    <img src="a.png">
    <img src="b.png">
    <img src="c.png">
  </div>
</div>

<script src="ultrasoul.js"></script>
<script>
  document.getElementsByClassName('lady-go-round').ladyGoRound();
</script>
```

#### `data-arg` Attribute

Specify the following parameters separated by spaces.

- margin right (px)
- interval (ms)
- duration (ms)
- font-size (px)

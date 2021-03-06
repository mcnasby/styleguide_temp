## Template

```
<div class="btn-examples">
	<!-- Default -->
	<button class="btn btn-default">
		Default
	</button>

	<!-- Primary -->
	<button class="btn btn-primary">
		Primary
	</button>
	
	<!-- Danger -->
	<button class="btn btn-danger">
		Danger
	</button>

	<!-- Link -->
	<button class="btn btn-link">
		Link
	</button>
</div>
```


## Styles

```css
/**
 * Buttons
 **/ 

button {
  -webkit-appearance: none;
  -moz-appearance: none;
}

.btn {
  padding: 4px 28px;
  border-radius: 0;
  border: 1px solid $blue-dark;
  outline: none;

  text-transform: uppercase;
  font-size: $font-size-xsmall;
  font-weight: $font-weight-base;
  line-height: $line-height-base;
  letter-spacing: 0.05rem;

  cursor: pointer;
}

.btn-primary {
	background-color: $blue;
	border-color: $blue-dark;
	color: white;

	&:hover {
		background-color: darken($blue, 5%);
		border-color: darken($blue, 5%);
	}
}

.btn-default {
	background-color: $white;
	border-color: $blue-dark;
	color: $blue;

	&:hover {
		background-color: $midnight-2;
	}
}

.btn-danger {
	background-color: $white;
	border-color: $red;
	color: $red;

	&:hover {
		background-color: $midnight-2;
	}
}

.btn-link {
	background-color: transparent;
	border-color: transparent;
	color: $blue;

	&:hover {
		background-color: $midnight-2;
	}
}

```
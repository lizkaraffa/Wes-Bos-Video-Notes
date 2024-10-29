# Understanding State

To prevent the error similar to previous videos don't use `.value.value` instead use `.current.value`.
Code should look like this:

const fish = {
		name: this.nameRef.current.value,
		price: this.priceRef.current.value,
		status: this.statusRef.current.value,
		desc: this.descRef.current.value,
		image: this.imageRef.current.value,
}

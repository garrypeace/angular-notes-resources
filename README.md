### Project structure

- Nx inspired structure with emphasis on smart (routed) and dumb (presentational) components: https://www.youtube.com/watch?v=7SDpTOLeqHE&t=121s

### Modules

-

### Lazy loading

-

### Forms

- 

### Tables

- Use ngTemplateOutlet to create a table component that is generic but also allows for easy extendability (e.g. adding column with different types of action buttons): https://www.youtube.com/watch?v=TZZApWysF9g

### Memory leaks / performance 

- takeUntilDestroyed: https://youtu.be/Cr4NRfZxaP0?si=nDc2L5JWVfn0E73w

- Expose only properties and public readonly values to the template.
- Compute values in the component and assign them to properties if needed.
- Use ngOnInit() or RxJS to prepare data before it hits the template.

### Unit testing

- https://youtu.be/lbiOP-VLKGI?si=-ujqU2w--5dq2Sav
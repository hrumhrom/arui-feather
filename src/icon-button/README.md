```jsx
<div className='row'>
    {['s', 'm', 'l', 'xl'].map(size => (
        <span
            key={ size }
            className='column l'
        >
            <IconButton size={ size } onClick={ () => { confirm('Подтвердите удаление') } }>
                <Icon size={ size } name='tool-close' />
            </IconButton>
        </span>
    ))}
</div>
```

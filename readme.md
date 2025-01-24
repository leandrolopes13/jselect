# JSelect

A lightweight and customizable JavaScript select/dropdown library with modern features.

## Sponsor

Publicidade BH - Apps, Sistemas e sites - https://www.publicidadebh.com.br/

## Features

- 🎯 Easy to integrate
- 🎨 Fully customizable styling
- 🔍 Search/filter functionality
- ⌨️ Keyboard navigation
- 📱 Mobile-friendly
- 🔄 Dynamic options loading
- ✨ Multiple selection support
- 🌐 Internationalization ready
- 🎭 Custom templates
- ⚡ Virtual scrolling for large lists

## Installation

```bash
npm install jselect
```

## Usage

```html
<!-- Include the CSS -->
<link rel="stylesheet" href="jselect.css">

<!-- Create your select element -->
<select multiple data-search placeholder="Selecione">
            <option value="1" data-icon="https://cdn2.iconfinder.com/data/icons/flags_gosquared/64/Brazil_flat.png">Valor 1</option>
            <option value="2">Valor 2</option>
            <option value="3">Valor 3</option>
            <option value="4">Valor 4</option>
            <option value="5">Valor 5</option>
            <option value="6">Valor 6</option>
        </select>

<!-- Include the JavaScript -->
<script src="jselect.min.js"></script>
<script>
    // Initialize JSelect
     $('select').jSelect({}).on('jSelect.change', function(event, values){
                console.log('jSelect.change', event.target, values);
            });
            $('select:eq(0)').jSelect('setValue', [1, 2]);
            $('select:eq(1)').jSelect('setValue', 1);
</script>
```

## Configuration

```javascript
$('select').jSelect({})
```

## API Reference

### Methods

- `setValue(value)`: Sets the selected value(s)

### Events

- `onChange`: Triggered when selection changes

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Leandro Lopes - leandrolopes.java@gmail.com - [GitHub Profile](https://github.com/leandrolopes13)

## Acknowledgments

- Thanks to all contributors who have helped make JSelect better
- Inspired by modern select libraries in the JavaScript ecosystem
# generamba-catalog

It's a shared catalog of templates for [Generamba](https://github.com/strongself/Generamba) code generator.

## Usage

1. Add templates to `Rambafile` .

    ```yaml:Rambafile
    ### Templates
    catalogs:
    - 'https://github.com/uhooi/generamba-catalog'
    templates:
    - {name: uhooi_viper}
    ```

2. Run `generamba template install` .

3. Run `generamba gen [Module name] [Tempalate name]` .

## Templates

- [uhooi_viper](https://github.com/uhooi/generamba-catalog/blob/master/uhooi_viper/uhooi_viper.rambaspec)

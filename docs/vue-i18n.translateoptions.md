<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [vue-i18n](./vue-i18n.md) &gt; [TranslateOptions](./vue-i18n.translateoptions.md)

## TranslateOptions type

\# translate

\#\# usages: // for example, locale messages key { 'foo.bar': 'hi {<!-- -->0<!-- -->} !' or 'hi {<!-- -->name<!-- -->} !' }

// no argument, context &amp; path only translate(context, 'foo.bar')

// list argument translate(context, 'foo.bar', \['kazupon'\])

// named argument translate(context, 'foo.bar', { name: 'kazupon' }<!-- -->)

// plural choice number translate(context, 'foo.bar', 2)

// plural choice number with name argument translate(context, 'foo.bar', { name: 'kazupon' }<!-- -->, 2)

// default message argument translate(context, 'foo.bar', 'this is default message')

// default message with named argument translate(context, 'foo.bar', { name: 'kazupon' }<!-- -->, 'Hello {<!-- -->name<!-- -->} !')

// use key as default message translate(context, 'hi {<!-- -->0<!-- -->} !', \['kazupon'\], { default: true }<!-- -->)

// locale option, override context.locale translate(context, 'foo.bar', { name: 'kazupon' }<!-- -->, { locale: 'ja' }<!-- -->)

// suppress localize miss warning option, override context.missingWarn translate(context, 'foo.bar', { name: 'kazupon' }<!-- -->, { missingWarn: false }<!-- -->)

// suppress localize fallback warning option, override context.fallbackWarn translate(context, 'foo.bar', { name: 'kazupon' }<!-- -->, { fallbackWarn: false }<!-- -->)

<b>Signature:</b>

```typescript
export declare type TranslateOptions = {
    list?: unknown[];
    named?: NamedValue;
    plural?: number;
    default?: string | boolean;
    locale?: Locale;
    missingWarn?: boolean;
    fallbackWarn?: boolean;
};
```

## API Report File for "@fluentui/react-link"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { IRefObject } from '@fluentui/utilities';
import { IStyle } from '@fluentui/style-utilities';
import { IStyleFunctionOrObject } from '@fluentui/utilities';
import { ITheme } from '@fluentui/style-utilities';
import * as React from 'react';

// @public (undocumented)
export interface ILink {
    focus(): void;
}

// @public @deprecated (undocumented)
export interface ILinkHTMLAttributes<T> extends React.HTMLAttributes<T> {
    [key: string]: any;
    // (undocumented)
    autoFocus?: boolean;
    // (undocumented)
    disabled?: boolean;
    // (undocumented)
    download?: any;
    // (undocumented)
    form?: string;
    // (undocumented)
    formAction?: string;
    // (undocumented)
    formEncType?: string;
    // (undocumented)
    formMethod?: string;
    // (undocumented)
    formNoValidate?: boolean;
    // (undocumented)
    formTarget?: string;
    // (undocumented)
    href?: string;
    // (undocumented)
    hrefLang?: string;
    // (undocumented)
    media?: string;
    // (undocumented)
    name?: string;
    // (undocumented)
    rel?: string;
    // (undocumented)
    target?: string;
    // (undocumented)
    type?: string;
    // (undocumented)
    value?: string | string[] | number;
}

// @public
export interface ILinkProps extends React.AnchorHTMLAttributes<HTMLAnchorElement | HTMLButtonElement | HTMLElement>, Omit<React.ButtonHTMLAttributes<HTMLAnchorElement | HTMLButtonElement | HTMLElement>, 'type'>, React.RefAttributes<HTMLElement> {
    [key: string]: any;
    as?: React.ElementType;
    componentRef?: IRefObject<ILink>;
    disabled?: boolean;
    href?: string;
    onClick?: (event: React.MouseEvent<HTMLAnchorElement | HTMLButtonElement | HTMLElement>) => void;
    rel?: string;
    styles?: IStyleFunctionOrObject<ILinkStyleProps, ILinkStyles>;
    target?: string;
    theme?: ITheme;
    type?: string;
}

// @public (undocumented)
export interface ILinkStyleProps {
    // (undocumented)
    className?: string;
    // (undocumented)
    isButton?: boolean;
    // (undocumented)
    isDisabled?: boolean;
    // (undocumented)
    theme: ITheme;
}

// @public (undocumented)
export interface ILinkStyles {
    // (undocumented)
    root: IStyle;
}

// @public (undocumented)
export const Link: React.FunctionComponent<ILinkProps>;

// @public (undocumented)
export const LinkBase: React.FunctionComponent<ILinkProps>;


// (No @packageDocumentation comment for this package)

```
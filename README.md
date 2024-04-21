# universal-currency-converter
An npm package to convert currency

## Installation
npm i universal-currency-converter

## Usage
import { convertCurrency } from 'universal-currency-converter';

async function example() {
    try {
        const result = await convertCurrency('USD', 'INR', 1);
        console.log(result); // Output the converted amount
    } catch (error) {
        console.error('Error converting currency:', error);
    }
}

example();

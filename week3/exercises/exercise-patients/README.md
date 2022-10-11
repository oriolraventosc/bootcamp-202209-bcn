# Ejercicio Patients (w3exPatients)

Crea un index.ts y declara una variable que almacene este array:

```
[
    {
        patient: {
            name: 'Luis',
            age: 25,
            sex: 'M'
        },
        daysInHospital: 3,
        diet: 'Low fiber'
    },
    {
        patient: {
            name: 'Marta',
            age: 56,
            sex: 'W'
        },
        daysInHospital: 5,
        diet: 'Diabetes'
    },
    {
        patient: {
            name: 'Julia',
            age: 38,
            sex: 'W'
        },
        daysInHospital: 1,
        diet: 'Salt free'
    },
    {
        patient: {
            name: 'Esteban',
            age: 40,
            sex: 'M'
        },
        daysInHospital: 3,
        diet: 'Diabetes'
    },
    {
        patient: {
            name: 'Arturo',
            age: 17,
            sex: 'M'
        },
        daysInHospital: 2,
        diet: 'Low fiber'
    },
    {
        patient: {
            name: 'Isabel',
            age: 63,
            sex: 'W'
        },
        daysInHospital: 6,
        diet: 'Salt free'
    }
];
```

En otro módulo haz una función, testeada, que reciba un array como éste y que devuelva un objeto con la siguiente forma:

```
{
    nPatients: (número de pacientes),
    nAdults: (número de pacientes mayores de edad),
    nDiabeticMen: (número de pacientes hombres con dieta para diabetes),
    totalDaysInHospital: (suma de los días de ingreso de todos los pacientes),
    averageAgeWomen: (edad media de las pacientes mujeres)
}
```

En index.ts llama a la función pasándole el array y consolea la salida.

**IMPORTANTE**: No puedes usar ninguna de estas estructuras:

- for, for ... of, for ... in, forEach(), while, do .. while

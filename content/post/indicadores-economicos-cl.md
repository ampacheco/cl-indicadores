---
title: "Principales Indicadores Económicos de Chile"
date: 2021-08-08
tags: ["finannzas", "chile", "economía", "negocios"]
draft: false
---

## Principales Indicadores Económicos
- USD
- UF
- Cobre

## USD Line Chart
{{< chart >}}
{
    type: 'line',
     data: {
  labels: ['Lunes 2/8','Martes 3/8', 'Miercoles 4/8', 'Jueves 5/8', 'Viernes 6/8'],
  datasets: [
    {
      label: 'Dataset 1',
      data: [760.2, 761.39, 774.54, 775.54, 776.69],
      borderColor: 'rgba(255, 99, 132, 0.2)',
      backgroundColor: 'rgba(255, 99, 132, 1)',
    },
    {
      label: 'Dataset 2',
      data: Utils.numbers(NUMBER_CFG),
      borderColor: 'rgba(255, 99, 132, 0.2)',
      backgroundColor: 'rgba(255, 99, 132, 1)',     
    }
  ]
},
    options: {
        responsive: true,
        plugins: {
            legend: {
                position: 'top',
            },
            title: {
                display: true,
                text: 'Valores USD'
            }
        }
    }
}
{{< /chart >}}

## USD
{{< chart >}}
{
    type: 'bar',
    data: {
        labels: [
            'L-02-Agosto', 
            'M-03-Agosto', 
            'Mx-04-Agosto', 
            'J-05-Agosto', 
            'V-06-Agosto', 
        ],
        datasets: [{
            label: 'Bar Chart',
            data: [760.2, 761.39, 774.54, 775.54, 776.69],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

## UF
{{< chart >}}
{
    type: 'bar',
    data: {
        labels: [
            'L-02-Agosto', 
            'M-03-Agosto', 
            'Mx-04-Agosto', 
            'J-05-Agosto', 
            'V-06-Agosto', 
        ],
        datasets: [{
            label: 'Bar Chart',
            data: [760.2, 761.39, 774.54, 775.54, 776.69],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

## Cobre

{{< chart >}}
{
    type: 'bar',
    data: {
        labels: [
            'L-02-Agosto', 
            'M-03-Agosto', 
            'Mx-04-Agosto', 
            'J-05-Agosto', 
            'V-06-Agosto', 
        ],
        datasets: [{
            label: 'Bar Chart',
            data: [760.2, 761.39, 774.54, 775.54, 776.69],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

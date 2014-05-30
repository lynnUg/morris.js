morris.js
=========

morris.js with small hack that adds axes titles

Example Usage 

Morris.Line({
                            element: 'morris-chart-line',
                            data: data,
                            lineColors:colors,
                            hideHover: 'auto',
                            xkey: 'date',
                            ykeys: ['The_Expend','The_Sale'],
                            labels: ['Expenditure','Sale'],
                            yaxisLabel:"Sales in UGX and Expenditure",
                            xaxisLabel:"Days"
  });

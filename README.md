# feedback-script
use this code snippet to automatically fill faculty feedback form on sgsitsindore.in

```
for (let i = 1; i <= 23; i++) {
    let sno;
    i < 10 ? sno = `0${i}` : sno = i;
    
    let radio = document.getElementById(`rptQuestion_ctl${sno}_RadioButtonList1_4`);
    radio.checked = true;    
}

```

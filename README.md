# DAY PICKER

This is a very light weight Javascript Date picker for your html.

## Default values
```
{
    position: "bottom left",
    reposition: true,
    format: "YYYY-MM-DD",
    toString: null,
}
```

## How to use:
Let you have a input component with id = "datepicker"

```
<input type="text" id="datepicker" autocomplete="off" />
```

Add daypicer.css file into your html head sectoin. 
```
<link rel="stylesheet" href="css/daypicker.css" />
```

Now add the following script on you html file
```
<script src="daypicker.js"></script>

<script>
    var picker = new DayPicker({
        field: document.getElementById("datepicker"),
        format: "DD/MMM/YYYY",
    });
</script>
```

That's it. Your component is ready to go. 


## How to run the project
This is very lite html project created using vitejs.

### Download and install dependency 
```
git clone git@github.com:nazmuldipu/DayPicker.git

cd DayPicker

npm install
```

### Run the project
```
npm run dev
```
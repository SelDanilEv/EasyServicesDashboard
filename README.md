# Dashboard Setup

Follow these steps to set up a new dashboard:

## 1. Update the Title

Update the title of the dashboard by modifying the `<h1>` element in the `index.html` file:

```html
<h1>New Dashboard Title</h1>
```

## 2. Update the HTML Title

Update the HTML title by modifying the `<title>` element in the index.html file:

```html
<h1>New Dashboard Title</h1>
```

### 3. Update services.json

Update the services.json file with the list of services you want to monitor. Here is an example structure:

```html
{
  "Category1": {
    "showByDefault": true,
    "urls": [
      { "name": "Service 1", "url": "https://service1.com/" },
      { "name": "Service 2", "url": "https://service2.com/" }
    ]
  },
  "Category2": {
    "showByDefault": false,
    "urls": [
      { "name": "Service 3", "url": "https://service3.com/" },
      { "name": "Service 4", "url": "https://service4.com/" }
    ]
  }
}
```


### 4. Open the Dashboard

Open the index.html file in a web browser to view the dashboard.

### 5. Feel free to modify the content as needed.
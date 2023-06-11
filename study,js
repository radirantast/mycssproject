function darkmode() {
    if (document.body.style.background == 'rgb(18, 18, 18)') {
        document.body.style.background = 'rgb(253, 248, 251)';
        document.body.style.color = 'black';
        document.getElementById('btn').value = 'Dark';
    } else {
        document.body.style.background = 'rgb(18, 18, 18)';
        document.body.style.color = 'white';
        document.getElementById('btn').value = 'White';
    }
};


class User {
    constructor() {
        this.data = null;
    }

    prom() {
        return new Promise(function (resolve, reject) {
            var api = fetch('https://jsonplaceholder.typicode.com/todos/1')
                .then(response => resolve(response.json()))
        })
    }

    async asnfun() {
        var pr = await this.prom();
        document.getElementById('newh2').innerHTML = JSON.stringify(pr, null, 1);
    };

}   

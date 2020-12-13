
let promise = new Promise((resolve,reject) => {});

queues promises
* all
* allSettled
* race

# async / await 

async function getNames(){
    return []
}

const getNames = async () => {
    return [];
}

---
### Getting Data 

* promise

axios.get("/orders/1")
.then(({data}) => {
    setText(JSON.stringify(data))
})

* await 

const {data} = await axios.get("/orders/1");

setText(JSON.stringify(data));

### handling errors 
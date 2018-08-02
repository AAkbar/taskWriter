<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tasks writer.</title>
    <style>
        *{
            -webkit-box-sizing: border-box;
                    box-sizing: border-box;
            padding: 0;
            margin: 0;
        }
        body{
            background-color: darkgoldenrod;
            font: 1.1em;
            font-family: verdana, sans-serif;
        }
        #container{
            width: 60%;
            margin: 0 auto;
            border: 10px inset khaki;
            background-color: aliceblue;
            border-radius: 20px;
            margin-top: 70px;
            -webkit-box-shadow: 10px 10px 30px grey;
                    box-shadow: 10px 10px 30px grey;
        }
        h1{
            text-align: center;
            text-transform: uppercase;
            padding: 20px;
        }
        form#enlist{
            padding: 1em;
        }
        input[type="text"]{
            width: 80%;
            height: 50px;
            font-size: 2em;
        }
        form{
            font-weight: 700;
        }
        input{
            margin: 0 auto;
            display: block;
            font-weight: 700;
        }
        ol{
            list-style: none;
            font-size: 1.7em;
            font-weight: 700;
            color: darkslategrey;
            width: 70%;
            margin: 0 auto;
            padding: 20px;
        }
        li{
            padding: 10px;
            text-transform: capitalize;
        }
        li:nth-of-type(even){
            background-color: blanchedalmond;
        }
        li:nth-of-type(odd){
            background-color: burlywood;
        }
        li:hover{
            background-color: darkgoldenrod;
            cursor: pointer;
        }
        #btn{
            width: 20%;
            font-size: 1.5em;
            margin-top: 10px;
            letter-spacing: 4px;
            background-color: darkgoldenrod;
            border: solid black 2px;
            border-radius: 10px;
            color: green;
            -webkit-box-shadow: black 0 0 30px 10px inset;
                    box-shadow: black 0 0 30px 10px inset;
            cursor: pointer;
        }
        #btn:active{
            -webkit-transform: translateY(-2px);
                -ms-transform: translateY(-2px);
                    transform: translateY(-2px);
        }
        .H{
            -webkit-transition: 1s ease-in all;
            -o-transition: 1s ease-in all;
            transition: 1s ease-in all;
            padding: 20px;
            cursor: pointer;
        }
        .H:hover{
            letter-spacing: 20px;
            padding: 50px;
        }
    </style>
</head>
<body>
    <div id="container">
        <form name="enlist" id="enlist">
           <h1 class="H">Enlist The Tasks</h1>
            <input type="text" id="enlistTask" name="enlistTask" placeholder="Walk The Dog!">
            <input type="submit" value="Enlist" id="btn" name="btn">
            <h1>Filter</h1>
            <input type="text" name="filterTask" id="filterTask" placeholder="Filter the tasks!">
        </form>
        <ol id="listOfTask">
            <li>Walk the Dog.</li>
            <li>Pay the Bills.</li>
        </ol>
    </div>
    <script>
        // variables
        let form = document.getElementById("enlist");
        let enlist = form.enlistTask;
        let filter = form.filterTask;
        let list = document.querySelector("#listOfTask");
        let btn = form.btn;
        let localMemory = [];
        
        if(localStorage.task){
            localMemory = JSON.parse(localStorage.getItem("task"));
            
            for(let i = 0; i < localMemory.length; i++){
                let li = document.createElement("li");
                let txt = document.createTextNode(localMemory[i]);
                li.appendChild(txt);
                list.append(li);
            }
        }
        
        // functions
        let filterTask = function(e){
            
            var lis = list.children;
            for(let i = 0; i < lis.length; i++){
                if((lis[i].innerHTML.toLowerCase().indexOf(filter.value.toLowerCase())) !== -1){
                    lis[i].style.display = "block";
                }else{
                    lis[i].style.display = "none";
                }
                
                if(filter.value === ""){
                    lis[i].style.display = "block";
                }
            }
        };
        
        let enlistingTasks = function(e){
            
            e.preventDefault();
            function checkForSameTask(a){
                let lis = list.children;
        
                for(let i = 0; i < lis.length; i++){
                    if(lis[i].innerHTML.toUpperCase() === a.toUpperCase()){
                        alert("You already Have listed The Task!");
                        return false;
                    }
                }
                return true;
            }
            
            //enlisting the task by checking condition
            if((enlist.value !== "") && (checkForSameTask(enlist.value))){
                
                if(localMemory.length !== 0){
                    localMemory.push(enlist.value);
                    localStorage.setItem("task", JSON.stringify(localMemory));
                }else{
                    localStorage.setItem("task", `["${enlist.value}"]`);
                }
                
                let li = document.createElement("li");
                let txt = document.createTextNode(enlist.value);
                li.appendChild(txt);
                list.append(li);
                enlist.value = "";
            }
            
            
        //End of function
        }
        
//        EventListeners
        
        filter.addEventListener("keyup", filterTask, false);
        btn.addEventListener("click", enlistingTasks, false);
    </script>
</body>
</html>



























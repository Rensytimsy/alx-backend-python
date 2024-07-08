Asyncio async operations...

Async IO
		 
asyncio ,async, await

asyncio is a python library that provide the functionality of async functions
asynchronous mainly means  not simultaneous or concurrent in time
async defines the beginning of a function that will make use of the await function
await is a function method that makes it easier to spare some time as something is being validated

async io is a concurrent programming design used in python programming language

Parallelism => This is a process where by programs are executed simultaneously.
Concurrency => It suggests that multiple tasks have the ability to run in an overlapping manner.

Below is a good example working with asyncio in python po
 	import asyncio
	import random
	async def delay_print(wait_time:int = 10) -> float:
		delayed_time = random.random() * wait_time
		await. Sleepsleep(delayed_time)
		return delayed_time

let's break down the code above
we are importing asyncio as i mentioned earlier it is a library that enables us to perform some asynchronous functionalities, the we import random to help us generate some random numbers in the range of 0 - 10 and returned in float form
Then next we define our async function named delay_print as the name suggests for sure there will be a delayed print that will be caused by the random number generated.
delay_print takes in one argument which is an integer.
we then make sure we get random numbers from the argument passed from delay_print, and thats where the random library comes in handy let me break the random method down for better understanding.
random in a function/method => random.random() * 5 this will return numbers between 1,2,3 and 4. Basically random returns random numbers between the range provided.

We then make use of the await method and sleep method. basically sleep is a STDL inbuilt command that makes the delay functionality note "according to me ".and finally return the random(delayed_time) saved after the random.random() function runs.



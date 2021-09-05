# go-cache
Project from the course platzi go avanzado. 

Go-cache handles requests of multiple jobs, and it makes sure that a job is only run once. If a job, that has been already requested, is requested again, it returns the result from the cache system

It also supports concurrency, if a job is requested multiples times at the same time, only one will run the actual process and the other will wait for the result to be deilvered.

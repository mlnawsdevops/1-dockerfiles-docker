# CMD image can be overridden at run time
# ENTRYPOINT can't overridden at run time. if we do that it will go and append to the ENTRYPOINT command
# for better results and best practices. CMD can provide arguments to ENTRYPOINT command. so, we can mention default args through CMD and we can override them at run time. 

#1
# FROM almalinux:9
# CMD ["ping", "google.com"]

#2
# FROM almalinux:9
# ENTRYPOINT ["ping", "google.com"]

#3
# cmd- argument and entrypoint- command
FROM almalinux:9
CMD ["google.com"] 
ENTRYPOINT ["ping"]
# RatingSystem
Rating system include backend(Expressjs) and frontend(Reactjs)

For both backend and Frontend install packages and run with "Yarn Start" command

API:
  
  GET: /api/rate => getting the list of rates
  
  Post: /api/rate => post rate
  
  Rate model ={
        id,
        sessionId,
        email,
        comment,
        rate
    };
    
    
  
Backend does not persist any data and works fully in memory

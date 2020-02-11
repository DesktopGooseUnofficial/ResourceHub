# Acid Goose


**A very weird version of the Goose we know and love <3**
#


Download: [AcidGoose.zip](https://github.com/DesktopGooseUnofficial/ResourceHub/releases/download/AcidGoose/AcidGoose.zip)


#
Goose Version: **v0.3**



Author: **⧹ F!NN ⧸#1580**

#
The code is kinda trash but I am still learning... Please dont blame me o.O
## Source code
```csharp 
public void PostTick(GooseEntity g)
        {
            
            float noicedirection = 0;

            ThreadPool.QueueUserWorkItem(dospinning);
            ThreadPool.QueueUserWorkItem(updateRotation);
            ThreadPool.QueueUserWorkItem(honk);


            
           

            void dospinning (object state)
            {
                
                
                while (true)
                {
                    noicedirection = noicedirection + 4f;

                   
                    
                    if (noicedirection == 360)
                    {
                        noicedirection = 0;
                    }
                    //Task.WaitAll(100);
                    Thread.Sleep(1);
                }
            }
            
            void updateRotation (object state) 
            { 
                while (true)
                {
                    g.direction = noicedirection;
                    
                    
                }
            }    
            
            void honk (object state)
            {
                
                
                while (true)
                {
                    API.Goose.playHonckSound();
                    Thread.Sleep(700);
                }
                
            } 


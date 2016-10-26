# n-s
build a N-S solver for CFD
Start with simple schemes and their stability, accuracy /n
  { 
    time scheme
    { 
      explicit
      implicit
      ab3
      rk4
      }
    space scheme, 1-d, 2-d, 3-d
    {
      center, forward, back finite difference
      specturm
      compact difference
      }
   }
   
   matrix generation
   
   boundary condition corrector
   
   eigen value solver
   
   solve simple problems
   {
      Poission
      advection-diffusion
   }
   
   N-S

Ryan Haddadi
mochi456@csu.fullerton.edu

Naeem Khayat Albirkdar
arnaeem@csu.fullerton.edu

PSEUDOCODE:
# sort_alternate

set start_at to first disk
set end_at to last_disk-1

while start_at less than end_at and not IS_SORTED
 
 for every other disk in the list from start_at to end_at
    
       
       if disk isn't identical to adjacent disk (and it's DARK)
       
        call swap function
       end if
      
  
  end for
  
  increment start_at
  
  decrement end_at

end while

# sort_lawnmower
while not IS_SORTED

  
  for each disk from left to right 
  
    if disk is black and adjacent[+1] disk isn't black
    
      call swap function
      
     end if
  
  end for
  
  if IS_SORTED
    return

  for each disk from right to left
      if disk is white and adjacent[-1] disk isn't white
          call swap function
      end if 
  end for
end while

return








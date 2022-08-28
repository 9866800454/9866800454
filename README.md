update branch_master    
set   bm_fund   = bm_fund
from branch_master with (nolock)   
where bm_fund=@fund and bm_branch  = @branch

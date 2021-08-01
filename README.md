def current_user
    @current_user ||= Student.find(session[:student_id]) if session[:student_id]
# || uses for Memoization to speed up. No need to check the code after "||" if there is a current_user.


  end

  def logged_in?
    !!current_user
# !! returns true if there is a current_user else it returns false

  end

# application_helper methods can be accessed by views whereas helper_methods in application controller can be accessed by every other parts.
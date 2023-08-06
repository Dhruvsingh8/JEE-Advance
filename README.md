# <script>
                                   const shifts = document.querySelectorAll('.shift');
                                   let activeIndex = 0;

                                   function showNextShift() {
                                   shifts[activeIndex].classList.remove('active');
                                   activeIndex = (activeIndex + 1) % shifts.length;
                                   shifts[activeIndex].classList.add('active');
                                   }

                                    // Change shift every 5 seconds (adjust the interval as needed)
                                   setInterval(showNextShift, 3000);
                                    </script>

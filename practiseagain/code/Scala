//HackerRank SuperDigit

object Solution {

  def main(args: Array[String]) {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution
*/

    println("Enter two numbers")
    val sc = scala.io.StdIn.readLine()
    val input1 = sc.split(" ")(0)
    val input2 = sc.split(" ")(1)

    val len = input1.length - 1
    val loopcount = Integer.parseInt(input2)

    def getSuperDigit(x: Int, y: Int, inputnum: String): Int = {
      var t: Int = 0

      for (j <- (1 to x)) {
        for (i <- (0 to y)) {
          t = t + inputnum(i).asDigit

          //   println("Sum of " + i +" time " +  inputnum(i) )
        }

      }

      // getSuperDigit(1,(t.toString().length()-1),  t.toString())
      
      if ( t.toString().length() ==1 ) return t
      else getSuperDigit(1,(t.toString().length()-1),  t.toString())
  
      
    }
      println( getSuperDigit(loopcount, len, input1))

  }
}

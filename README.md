package DemoclassMavenProject.Demoartifact1;

import static org.junit.Assert.*;

import java.io.ByteArrayInputStream;
import java.io.ByteArrayOutputStream;
import java.io.PrintStream;

import javax.print.DocFlavor.INPUT_STREAM;

import org.testng.annotations.Test;



public class DemoTest extends Democlass{
	
	@Test
	public void test_is_triangle_1() {
		assertTrue(Democlass.isTriangle(3,4,5));
		
	}
	@Test
	public void test_is_triangle_2() {
		assertTrue(Democlass.isTriangle(5,12,13));
		
	}
	
	@Test
	public void test_is_triangle_3() {
		assertTrue(Democlass.isTriangle(5,13,12));
		
	}
	
	@Test
	public void test_is_triangle_4() {
		assertTrue(Democlass.isTriangle(12,5,13));
		
	}
	
	@Test
	public void test_is_NOTtriangle_1() {
		assertFalse(Democlass.isTriangle(13,7,5));
		
	}
	
	@Test
	public void test_is_NOTtriangle_2() {
		assertFalse(Democlass.isTriangle(5,9,3));
		
	}
	
	@Test
	public void test_is_NOTtriangle_3() {
		assertFalse(Democlass.isTriangle(1,2,-1));
		
	}
 }

 -----------------------------------------------------------------------
 OutPut -

 [RemoteTestNG] detected TestNG version 6.14.3
PASSED: test_is_NOTtriangle_1
PASSED: test_is_NOTtriangle_2
PASSED: test_is_NOTtriangle_3
PASSED: test_is_triangle_1
PASSED: test_is_triangle_2
PASSED: test_is_triangle_3
PASSED: test_is_triangle_4

===============================================
    Default test
    Tests run: 7, Failures: 0, Skips: 0
===============================================


===============================================
Default suite
Total tests run: 7, Failures: 0, Skips: 0
===============================================

